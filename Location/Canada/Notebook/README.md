Linux in Canada - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Canada.

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

Total: 3152

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Google        | Droid                       | [40550baeb8](https://linux-hardware.org/?probe=40550baeb8) | Oct 01, 2022 |
| Dell          | Latitude E5530 non-vPro     | [b2d146f923](https://linux-hardware.org/?probe=b2d146f923) | Oct 01, 2022 |
| Samsung       | 950XDB/951XDB/950XDY        | [5c5353c8b6](https://linux-hardware.org/?probe=5c5353c8b6) | Oct 01, 2022 |
| Dell          | Latitude E4300              | [a860d9a446](https://linux-hardware.org/?probe=a860d9a446) | Sep 30, 2022 |
| Lenovo        | ThinkPad T480 20L5001FUS    | [a7e0da7aa4](https://linux-hardware.org/?probe=a7e0da7aa4) | Sep 30, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | [46ef409fa9](https://linux-hardware.org/?probe=46ef409fa9) | Sep 30, 2022 |
| HP            | Notebook                    | [6b7215bcba](https://linux-hardware.org/?probe=6b7215bcba) | Sep 29, 2022 |
| Dell          | Latitude E6430              | [f3e5e0005d](https://linux-hardware.org/?probe=f3e5e0005d) | Sep 29, 2022 |
| Lenovo        | ThinkPad T460 20FMS43J0V    | [0453cd781f](https://linux-hardware.org/?probe=0453cd781f) | Sep 28, 2022 |
| Gigabyte      | AORUS 15P YD                | [61e297be71](https://linux-hardware.org/?probe=61e297be71) | Sep 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [89c48e7d5a](https://linux-hardware.org/?probe=89c48e7d5a) | Sep 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [b39aefdcda](https://linux-hardware.org/?probe=b39aefdcda) | Sep 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [fb2de59c3f](https://linux-hardware.org/?probe=fb2de59c3f) | Sep 27, 2022 |
| ASUSTek       | G73Jh                       | [e5405dd3d8](https://linux-hardware.org/?probe=e5405dd3d8) | Sep 27, 2022 |
| ASUSTek       | G73Jh                       | [ac96a56edf](https://linux-hardware.org/?probe=ac96a56edf) | Sep 27, 2022 |
| HP            | Laptop 15-dw3xxx            | [d7dcd834e2](https://linux-hardware.org/?probe=d7dcd834e2) | Sep 27, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [4f58ff1174](https://linux-hardware.org/?probe=4f58ff1174) | Sep 26, 2022 |
| Acer          | Aspire A515-55              | [a9ac678198](https://linux-hardware.org/?probe=a9ac678198) | Sep 26, 2022 |
| Acer          | Aspire A515-55              | [8e66a480f3](https://linux-hardware.org/?probe=8e66a480f3) | Sep 26, 2022 |
| ASUSTek       | K52N                        | [8d7b00011f](https://linux-hardware.org/?probe=8d7b00011f) | Sep 26, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [52a86d0701](https://linux-hardware.org/?probe=52a86d0701) | Sep 26, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [683aa83ea4](https://linux-hardware.org/?probe=683aa83ea4) | Sep 26, 2022 |
| MSI           | GS65 Stealth 9SE            | [0c8e0eb1f5](https://linux-hardware.org/?probe=0c8e0eb1f5) | Sep 26, 2022 |
| MSI           | GE75 Raider 8SF             | [094a9b115b](https://linux-hardware.org/?probe=094a9b115b) | Sep 26, 2022 |
| Apple         | MacBookPro14,1              | [f5e9524bff](https://linux-hardware.org/?probe=f5e9524bff) | Sep 25, 2022 |
| Dell          | Inspiron 1440               | [c928a944c0](https://linux-hardware.org/?probe=c928a944c0) | Sep 24, 2022 |
| Dell          | Latitude E5510              | [04f4e9a803](https://linux-hardware.org/?probe=04f4e9a803) | Sep 24, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | [70404f465f](https://linux-hardware.org/?probe=70404f465f) | Sep 24, 2022 |
| HP            | Notebook                    | [f4e47792c1](https://linux-hardware.org/?probe=f4e47792c1) | Sep 24, 2022 |
| Lenovo        | ThinkPad T61p 64575KU       | [a5e3ca7c25](https://linux-hardware.org/?probe=a5e3ca7c25) | Sep 23, 2022 |
| Valve         | Jupiter                     | [ca6d2abcd9](https://linux-hardware.org/?probe=ca6d2abcd9) | Sep 23, 2022 |
| Valve         | Jupiter                     | [bea162d6e3](https://linux-hardware.org/?probe=bea162d6e3) | Sep 22, 2022 |
| Lenovo        | ThinkPad Edge E530 3259C... | [cdaec9c224](https://linux-hardware.org/?probe=cdaec9c224) | Sep 22, 2022 |
| Acer          | Aspire A515-55              | [fb1cce613c](https://linux-hardware.org/?probe=fb1cce613c) | Sep 22, 2022 |
| ASUSTek       | G73Jh                       | [58b83fee74](https://linux-hardware.org/?probe=58b83fee74) | Sep 22, 2022 |
| ASUSTek       | G73Jh                       | [e40a8996c4](https://linux-hardware.org/?probe=e40a8996c4) | Sep 22, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | [dd994c3f70](https://linux-hardware.org/?probe=dd994c3f70) | Sep 22, 2022 |
| Razer         | Blade                       | [c835fe2f90](https://linux-hardware.org/?probe=c835fe2f90) | Sep 21, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | [79f0e7d5a2](https://linux-hardware.org/?probe=79f0e7d5a2) | Sep 21, 2022 |
| Valve         | Jupiter                     | [1c7bc3efcf](https://linux-hardware.org/?probe=1c7bc3efcf) | Sep 21, 2022 |
| Dell          | Latitude E4310              | [06dc3db422](https://linux-hardware.org/?probe=06dc3db422) | Sep 20, 2022 |
| Valve         | Jupiter                     | [090e33f643](https://linux-hardware.org/?probe=090e33f643) | Sep 20, 2022 |
| Acer          | Aspire E5-532               | [1d0f80e0f1](https://linux-hardware.org/?probe=1d0f80e0f1) | Sep 20, 2022 |
| Acer          | Aspire E5-532               | [f349ec9700](https://linux-hardware.org/?probe=f349ec9700) | Sep 20, 2022 |
| Acer          | Nitro AN517-51              | [7bd22a5e38](https://linux-hardware.org/?probe=7bd22a5e38) | Sep 20, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | [66596e407c](https://linux-hardware.org/?probe=66596e407c) | Sep 19, 2022 |
| ASUSTek       | GL502VMK                    | [9776f2c20c](https://linux-hardware.org/?probe=9776f2c20c) | Sep 19, 2022 |
| Acer          | Aspire A515-55              | [c932451f8e](https://linux-hardware.org/?probe=c932451f8e) | Sep 19, 2022 |
| Dell          | Latitude E6540              | [d3140eaa89](https://linux-hardware.org/?probe=d3140eaa89) | Sep 19, 2022 |
| Dell          | Latitude E6540              | [7bf393c147](https://linux-hardware.org/?probe=7bf393c147) | Sep 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [b707354c65](https://linux-hardware.org/?probe=b707354c65) | Sep 18, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | [2e1e251503](https://linux-hardware.org/?probe=2e1e251503) | Sep 18, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | [5f56e8b10f](https://linux-hardware.org/?probe=5f56e8b10f) | Sep 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [50da0a8acf](https://linux-hardware.org/?probe=50da0a8acf) | Sep 18, 2022 |
| Dell          | XPS 15 7590                 | [a191bd2a9f](https://linux-hardware.org/?probe=a191bd2a9f) | Sep 18, 2022 |
| Razer         | Blade 14 - RZ09-0370        | [1f9f8ee511](https://linux-hardware.org/?probe=1f9f8ee511) | Sep 18, 2022 |
| HP            | Laptop 15-ef0xxx            | [19d0260ef6](https://linux-hardware.org/?probe=19d0260ef6) | Sep 17, 2022 |
| Lenovo        | ThinkPad P17 Gen 1 20SQS... | [e31f54dfa3](https://linux-hardware.org/?probe=e31f54dfa3) | Sep 16, 2022 |
| Valve         | Jupiter                     | [28a40721a8](https://linux-hardware.org/?probe=28a40721a8) | Sep 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [70a944e816](https://linux-hardware.org/?probe=70a944e816) | Sep 16, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [4ee2b37edf](https://linux-hardware.org/?probe=4ee2b37edf) | Sep 16, 2022 |
| Lenovo        | ThinkPad T430 2347G4U       | [aa5d8a2fc6](https://linux-hardware.org/?probe=aa5d8a2fc6) | Sep 15, 2022 |
| Lenovo        | ThinkPad T430 2347G4U       | [8e62e03e0b](https://linux-hardware.org/?probe=8e62e03e0b) | Sep 15, 2022 |
| Google        | Droid                       | [b4acc4ee70](https://linux-hardware.org/?probe=b4acc4ee70) | Sep 15, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [45309244c3](https://linux-hardware.org/?probe=45309244c3) | Sep 15, 2022 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | [efb36530f1](https://linux-hardware.org/?probe=efb36530f1) | Sep 14, 2022 |
| Lenovo        | ThinkPad T510 4349BR8       | [d60b0c8539](https://linux-hardware.org/?probe=d60b0c8539) | Sep 14, 2022 |
| Dell          | Inspiron 15-7568            | [c3b834caec](https://linux-hardware.org/?probe=c3b834caec) | Sep 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [3f34e5ed01](https://linux-hardware.org/?probe=3f34e5ed01) | Sep 14, 2022 |
| Dell          | Inspiron 5575               | [1ae871a545](https://linux-hardware.org/?probe=1ae871a545) | Sep 14, 2022 |
| Dell          | XPS 9315                    | [77ecec9e58](https://linux-hardware.org/?probe=77ecec9e58) | Sep 12, 2022 |
| Dell          | XPS 9315                    | [cfaae58ffa](https://linux-hardware.org/?probe=cfaae58ffa) | Sep 12, 2022 |
| Razer         | Blade 14 - RZ09-0370        | [47b15d6b6c](https://linux-hardware.org/?probe=47b15d6b6c) | Sep 12, 2022 |
| Acer          | Aspire A515-55              | [5a114e6867](https://linux-hardware.org/?probe=5a114e6867) | Sep 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [276e6547f9](https://linux-hardware.org/?probe=276e6547f9) | Sep 11, 2022 |
| Dell          | Latitude 3190               | [14d836c020](https://linux-hardware.org/?probe=14d836c020) | Sep 11, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | [f8be9f1680](https://linux-hardware.org/?probe=f8be9f1680) | Sep 11, 2022 |
| Acer          | Swift SF314-52              | [51857d9758](https://linux-hardware.org/?probe=51857d9758) | Sep 11, 2022 |
| Lenovo        | ThinkPad L460 20FVS1BC0S    | [e668edf31d](https://linux-hardware.org/?probe=e668edf31d) | Sep 11, 2022 |
| MSI           | Alpha 15 B5EEK              | [cf9447ce8c](https://linux-hardware.org/?probe=cf9447ce8c) | Sep 10, 2022 |
| Valve         | Jupiter                     | [2c95ed7c92](https://linux-hardware.org/?probe=2c95ed7c92) | Sep 10, 2022 |
| Dell          | Vostro 3550                 | [2e9e331465](https://linux-hardware.org/?probe=2e9e331465) | Sep 10, 2022 |
| Toshiba       | Satellite P200              | [c49fec0796](https://linux-hardware.org/?probe=c49fec0796) | Sep 09, 2022 |
| Valve         | Jupiter                     | [48df4850fe](https://linux-hardware.org/?probe=48df4850fe) | Sep 09, 2022 |
| ASUSTek       | ROG Zephyrus S17 GX703HS... | [041c6dac05](https://linux-hardware.org/?probe=041c6dac05) | Sep 08, 2022 |
| Valve         | Jupiter                     | [3c4865fc8c](https://linux-hardware.org/?probe=3c4865fc8c) | Sep 08, 2022 |
| HP            | Pavilion dv6700             | [6f32b647ec](https://linux-hardware.org/?probe=6f32b647ec) | Sep 07, 2022 |
| Valve         | Jupiter                     | [47baad2eed](https://linux-hardware.org/?probe=47baad2eed) | Sep 07, 2022 |
| Valve         | Jupiter                     | [090d406ac3](https://linux-hardware.org/?probe=090d406ac3) | Sep 07, 2022 |
| Lenovo        | ThinkPad T410 2516CTO       | [d3d092e789](https://linux-hardware.org/?probe=d3d092e789) | Sep 07, 2022 |
| Lenovo        | ThinkPad T410 2516CTO       | [424adc035f](https://linux-hardware.org/?probe=424adc035f) | Sep 07, 2022 |
| Lenovo        | ThinkPad X230 23252UU       | [0853f0ca45](https://linux-hardware.org/?probe=0853f0ca45) | Sep 05, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [3c578ac6c8](https://linux-hardware.org/?probe=3c578ac6c8) | Sep 05, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [e6117fb016](https://linux-hardware.org/?probe=e6117fb016) | Sep 05, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [e8887916fa](https://linux-hardware.org/?probe=e8887916fa) | Sep 05, 2022 |
| Acer          | Swift SF314-42              | [12fbd247f5](https://linux-hardware.org/?probe=12fbd247f5) | Sep 05, 2022 |
| Dell          | Inspiron 15 3525            | [0ec2aca595](https://linux-hardware.org/?probe=0ec2aca595) | Sep 04, 2022 |
| ASUSTek       | X553MA                      | [9567e25730](https://linux-hardware.org/?probe=9567e25730) | Sep 03, 2022 |
| Lenovo        | ThinkPad T410 2518F5U       | [9b61c2fbcc](https://linux-hardware.org/?probe=9b61c2fbcc) | Sep 02, 2022 |
| ASUSTek       | X553MA                      | [18756268eb](https://linux-hardware.org/?probe=18756268eb) | Sep 02, 2022 |
| Valve         | Jupiter                     | [b3b1ffd7ff](https://linux-hardware.org/?probe=b3b1ffd7ff) | Sep 02, 2022 |
| Lenovo        | ThinkPad T410 2518F5U       | [95e8dcce67](https://linux-hardware.org/?probe=95e8dcce67) | Sep 02, 2022 |
| Acer          | Aspire 5810T                | [6f807b1a84](https://linux-hardware.org/?probe=6f807b1a84) | Sep 01, 2022 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | [d6e9455a63](https://linux-hardware.org/?probe=d6e9455a63) | Aug 31, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | [6eeadaf886](https://linux-hardware.org/?probe=6eeadaf886) | Aug 31, 2022 |
| ASUSTek       | K401UQK                     | [4f026584d7](https://linux-hardware.org/?probe=4f026584d7) | Aug 31, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | [56e8f54a3e](https://linux-hardware.org/?probe=56e8f54a3e) | Aug 31, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [20da9d42a4](https://linux-hardware.org/?probe=20da9d42a4) | Aug 30, 2022 |
| Dell          | Inspiron 15-3567            | [39ae8218f6](https://linux-hardware.org/?probe=39ae8218f6) | Aug 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [a8acbb8d0b](https://linux-hardware.org/?probe=a8acbb8d0b) | Aug 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [20bea980d2](https://linux-hardware.org/?probe=20bea980d2) | Aug 28, 2022 |
| Lenovo        | ThinkPad T430 2349DG5       | [740898521d](https://linux-hardware.org/?probe=740898521d) | Aug 27, 2022 |
| Lenovo        | ThinkPad T430 2344BMU       | [c164d20c15](https://linux-hardware.org/?probe=c164d20c15) | Aug 26, 2022 |
| Lenovo        | ThinkPad T460s 20F9004NU... | [04f9f63255](https://linux-hardware.org/?probe=04f9f63255) | Aug 26, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [83377b24dc](https://linux-hardware.org/?probe=83377b24dc) | Aug 25, 2022 |
| MSI           | WF75 10TK                   | [8f395376ba](https://linux-hardware.org/?probe=8f395376ba) | Aug 25, 2022 |
| Lenovo        | ThinkPad T420s 417152U      | [73a97b425c](https://linux-hardware.org/?probe=73a97b425c) | Aug 25, 2022 |
| Acer          | Swift SFX14-41G             | [8d1cad5e52](https://linux-hardware.org/?probe=8d1cad5e52) | Aug 25, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [d2e2d5484c](https://linux-hardware.org/?probe=d2e2d5484c) | Aug 25, 2022 |
| Google        | Rabbid                      | [8049c3894c](https://linux-hardware.org/?probe=8049c3894c) | Aug 24, 2022 |
| Lenovo        | 14w 81MQ000JUS              | [1ff769c6ef](https://linux-hardware.org/?probe=1ff769c6ef) | Aug 23, 2022 |
| Valve         | Jupiter                     | [ba1940016e](https://linux-hardware.org/?probe=ba1940016e) | Aug 23, 2022 |
| Valve         | Jupiter                     | [04b0de9007](https://linux-hardware.org/?probe=04b0de9007) | Aug 22, 2022 |
| System76      | Oryx Pro                    | [7c763e43c6](https://linux-hardware.org/?probe=7c763e43c6) | Aug 21, 2022 |
| HP            | Pavilion 15                 | [c8d31e4708](https://linux-hardware.org/?probe=c8d31e4708) | Aug 21, 2022 |
| Dell          | Inspiron 15-5578            | [a0ff8934e5](https://linux-hardware.org/?probe=a0ff8934e5) | Aug 21, 2022 |
| Sony          | VPCEB12FD                   | [f98be4240a](https://linux-hardware.org/?probe=f98be4240a) | Aug 20, 2022 |
| Lenovo        | ThinkPad T500 2055A38       | [f37fce9f01](https://linux-hardware.org/?probe=f37fce9f01) | Aug 20, 2022 |
| Toshiba       | PORTEGE M780                | [8b7e72c5d9](https://linux-hardware.org/?probe=8b7e72c5d9) | Aug 20, 2022 |
| MSI           | Sword 15 A11UD              | [ca0fbaa451](https://linux-hardware.org/?probe=ca0fbaa451) | Aug 19, 2022 |
| MSI           | Sword 15 A11UD              | [565a6f9022](https://linux-hardware.org/?probe=565a6f9022) | Aug 19, 2022 |
| HP            | EliteBook 8460p             | [1eca9d2f2d](https://linux-hardware.org/?probe=1eca9d2f2d) | Aug 19, 2022 |
| Dell          | Latitude E6410              | [3304a70394](https://linux-hardware.org/?probe=3304a70394) | Aug 19, 2022 |
| Lenovo        | ThinkPad T460s 20F9004NU... | [3b35e8e9da](https://linux-hardware.org/?probe=3b35e8e9da) | Aug 17, 2022 |
| Lenovo        | ThinkPad T470s 20HFCTO1W... | [4d5eb5e332](https://linux-hardware.org/?probe=4d5eb5e332) | Aug 15, 2022 |
| ASUSTek       | X555LAB                     | [5171fd1732](https://linux-hardware.org/?probe=5171fd1732) | Aug 15, 2022 |
| Lenovo        | ThinkPad T460s 20F9004NU... | [e09e349f03](https://linux-hardware.org/?probe=e09e349f03) | Aug 15, 2022 |
| Valve         | Jupiter                     | [9ab7a2b695](https://linux-hardware.org/?probe=9ab7a2b695) | Aug 15, 2022 |
| Dell          | XPS 15 9500                 | [08ef9ef965](https://linux-hardware.org/?probe=08ef9ef965) | Aug 14, 2022 |
| Lenovo        | ThinkPad E550 20DF0040CA    | [0f657d4798](https://linux-hardware.org/?probe=0f657d4798) | Aug 14, 2022 |
| HP            | ENVY m6                     | [74d1a937cf](https://linux-hardware.org/?probe=74d1a937cf) | Aug 14, 2022 |
| Apple         | MacBookPro12,1              | [8b417889e1](https://linux-hardware.org/?probe=8b417889e1) | Aug 13, 2022 |
| Dell          | G3 3590                     | [fbe948e194](https://linux-hardware.org/?probe=fbe948e194) | Aug 13, 2022 |
| Toshiba       | PORTEGE M780                | [b7304a84fd](https://linux-hardware.org/?probe=b7304a84fd) | Aug 13, 2022 |
| Valve         | Jupiter                     | [3a1e95f5d5](https://linux-hardware.org/?probe=3a1e95f5d5) | Aug 12, 2022 |
| Dell          | Latitude 7420               | [26cd6bbb87](https://linux-hardware.org/?probe=26cd6bbb87) | Aug 12, 2022 |
| HP            | Pavilion 15                 | [462769d45e](https://linux-hardware.org/?probe=462769d45e) | Aug 11, 2022 |
| Lenovo        | IdeaPad Y410P 20216         | [df3068aea1](https://linux-hardware.org/?probe=df3068aea1) | Aug 10, 2022 |
| Lenovo        | ThinkPad T460s 20F9004NU... | [21044cebb3](https://linux-hardware.org/?probe=21044cebb3) | Aug 10, 2022 |
| HP            | ProBook 4540s               | [426365299d](https://linux-hardware.org/?probe=426365299d) | Aug 10, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | [b188230a8a](https://linux-hardware.org/?probe=b188230a8a) | Aug 10, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | [7586fd5a58](https://linux-hardware.org/?probe=7586fd5a58) | Aug 10, 2022 |
| HP            | Laptop 17-by1xxx            | [1be4a11102](https://linux-hardware.org/?probe=1be4a11102) | Aug 09, 2022 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | [59250f2c2f](https://linux-hardware.org/?probe=59250f2c2f) | Aug 08, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [10d18cd30b](https://linux-hardware.org/?probe=10d18cd30b) | Aug 08, 2022 |
| Razer         | Book 13 - RZ09-0357         | [c4a323d350](https://linux-hardware.org/?probe=c4a323d350) | Aug 06, 2022 |
| ASUSTek       | UX303UA                     | [73145490fa](https://linux-hardware.org/?probe=73145490fa) | Aug 06, 2022 |
| Apple         | MacBookPro9,2               | [a1b55cc875](https://linux-hardware.org/?probe=a1b55cc875) | Aug 06, 2022 |
| Acer          | Aspire 5742                 | [b1ec54ce80](https://linux-hardware.org/?probe=b1ec54ce80) | Aug 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [4acbeffc03](https://linux-hardware.org/?probe=4acbeffc03) | Aug 05, 2022 |
| Dell          | XPS 15 9520                 | [385e290982](https://linux-hardware.org/?probe=385e290982) | Aug 03, 2022 |
| Dell          | XPS 15 9520                 | [c7789bc8ca](https://linux-hardware.org/?probe=c7789bc8ca) | Aug 03, 2022 |
| Google        | Droid                       | [15d4518ba0](https://linux-hardware.org/?probe=15d4518ba0) | Aug 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [f79a1d3402](https://linux-hardware.org/?probe=f79a1d3402) | Aug 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [b2e4380743](https://linux-hardware.org/?probe=b2e4380743) | Aug 03, 2022 |
| Alienware     | x17 R2                      | [48772fabd8](https://linux-hardware.org/?probe=48772fabd8) | Aug 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [0df3af0bc5](https://linux-hardware.org/?probe=0df3af0bc5) | Aug 02, 2022 |
| Alienware     | x17 R2                      | [606b777651](https://linux-hardware.org/?probe=606b777651) | Aug 02, 2022 |
| Valve         | Jupiter                     | [bfddbf1d22](https://linux-hardware.org/?probe=bfddbf1d22) | Aug 02, 2022 |
| HP            | Unknown                     | [bd6c9221e7](https://linux-hardware.org/?probe=bd6c9221e7) | Aug 02, 2022 |
| HP            | Pavilion 15                 | [442aaa6069](https://linux-hardware.org/?probe=442aaa6069) | Aug 01, 2022 |
| Valve         | Jupiter                     | [e4c6300b68](https://linux-hardware.org/?probe=e4c6300b68) | Aug 01, 2022 |
| HP            | Laptop 14-dq4xxx            | [1e57f77386](https://linux-hardware.org/?probe=1e57f77386) | Aug 01, 2022 |
| ASUSTek       | G73Jh                       | [ec1e513893](https://linux-hardware.org/?probe=ec1e513893) | Aug 01, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [15382de4bf](https://linux-hardware.org/?probe=15382de4bf) | Aug 01, 2022 |
| Dell          | Latitude E5450              | [b7618f5c14](https://linux-hardware.org/?probe=b7618f5c14) | Jul 31, 2022 |
| Dell          | Latitude E5450              | [2c6979fb39](https://linux-hardware.org/?probe=2c6979fb39) | Jul 31, 2022 |
| HP            | Laptop 15-dy3xxx            | [e54cde5e86](https://linux-hardware.org/?probe=e54cde5e86) | Jul 31, 2022 |
| Fujitsu       | STYLISTIC Q702              | [2fe4fe7fe5](https://linux-hardware.org/?probe=2fe4fe7fe5) | Jul 30, 2022 |
| AMI           | T3 MRD                      | [7e0a2ced92](https://linux-hardware.org/?probe=7e0a2ced92) | Jul 29, 2022 |
| Lenovo        | ThinkPad T440s 20ARS4PR0... | [5b91ff037d](https://linux-hardware.org/?probe=5b91ff037d) | Jul 29, 2022 |
| Clevo         | W150HNM/W170HN              | [31c83153b5](https://linux-hardware.org/?probe=31c83153b5) | Jul 29, 2022 |
| MSI           | GF75 Thin 9SC               | [a6113f2e35](https://linux-hardware.org/?probe=a6113f2e35) | Jul 29, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [03b39a36f1](https://linux-hardware.org/?probe=03b39a36f1) | Jul 29, 2022 |
| Valve         | Jupiter                     | [dffaa71aed](https://linux-hardware.org/?probe=dffaa71aed) | Jul 28, 2022 |
| Dell          | Latitude E7440              | [ff1e9aae86](https://linux-hardware.org/?probe=ff1e9aae86) | Jul 28, 2022 |
| Lenovo        | ThinkPad X270 20HMS0GJ00    | [fa45b52c07](https://linux-hardware.org/?probe=fa45b52c07) | Jul 27, 2022 |
| Lenovo        | ThinkPad T420 4236CTO       | [6797b09b3b](https://linux-hardware.org/?probe=6797b09b3b) | Jul 27, 2022 |
| Dell          | XPS 17 9720                 | [5f7787d9e3](https://linux-hardware.org/?probe=5f7787d9e3) | Jul 27, 2022 |
| HP            | Stream Laptop 14-cb1XX      | [c5f4ae1ac4](https://linux-hardware.org/?probe=c5f4ae1ac4) | Jul 26, 2022 |
| Lenovo        | ThinkPad W530 24472SU       | [52f731db42](https://linux-hardware.org/?probe=52f731db42) | Jul 25, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | [acc848feda](https://linux-hardware.org/?probe=acc848feda) | Jul 24, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | [0084e69574](https://linux-hardware.org/?probe=0084e69574) | Jul 24, 2022 |
| HP            | EliteBook Folio 1040 G1     | [4c0cb4fd92](https://linux-hardware.org/?probe=4c0cb4fd92) | Jul 23, 2022 |
| Apple         | MacBookPro8,2               | [e31685e3ae](https://linux-hardware.org/?probe=e31685e3ae) | Jul 23, 2022 |
| Apple         | MacBookAir7,2               | [a86b33bdc2](https://linux-hardware.org/?probe=a86b33bdc2) | Jul 22, 2022 |
| Lenovo        | ThinkPad T500 2055A38       | [3b2f2c3bea](https://linux-hardware.org/?probe=3b2f2c3bea) | Jul 22, 2022 |
| Dell          | Precision 7560              | [c76f72f8c7](https://linux-hardware.org/?probe=c76f72f8c7) | Jul 21, 2022 |
| Dell          | G3 3590                     | [920eed9524](https://linux-hardware.org/?probe=920eed9524) | Jul 19, 2022 |
| ASUSTek       | X555QA                      | [a34b1c5684](https://linux-hardware.org/?probe=a34b1c5684) | Jul 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [75990d47d7](https://linux-hardware.org/?probe=75990d47d7) | Jul 17, 2022 |
| Lenovo        | ThinkPad T500 2055A38       | [e8b9689526](https://linux-hardware.org/?probe=e8b9689526) | Jul 17, 2022 |
| ASUSTek       | U30Jc                       | [3a6a0ec169](https://linux-hardware.org/?probe=3a6a0ec169) | Jul 17, 2022 |
| HP            | Laptop 14-dk1xxx            | [cf03561efa](https://linux-hardware.org/?probe=cf03561efa) | Jul 17, 2022 |
| Acer          | Aspire A515-55              | [e762750617](https://linux-hardware.org/?probe=e762750617) | Jul 16, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [a6e936c29d](https://linux-hardware.org/?probe=a6e936c29d) | Jul 16, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [d465259da1](https://linux-hardware.org/?probe=d465259da1) | Jul 16, 2022 |
| Acer          | Aspire A515-55              | [c020ff87e8](https://linux-hardware.org/?probe=c020ff87e8) | Jul 16, 2022 |
| HP            | Pavilion g6                 | [556c813157](https://linux-hardware.org/?probe=556c813157) | Jul 16, 2022 |
| HP            | Notebook                    | [8ef9afa771](https://linux-hardware.org/?probe=8ef9afa771) | Jul 16, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [46ef1a2cd6](https://linux-hardware.org/?probe=46ef1a2cd6) | Jul 14, 2022 |
| AMI           | T3 MRD                      | [d29d5d14c8](https://linux-hardware.org/?probe=d29d5d14c8) | Jul 14, 2022 |
| Lenovo        | ThinkPad T420s 417152U      | [e5c9e4e4d9](https://linux-hardware.org/?probe=e5c9e4e4d9) | Jul 13, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [34c2c24b3b](https://linux-hardware.org/?probe=34c2c24b3b) | Jul 11, 2022 |
| Dell          | Latitude 5510               | [5f1abb9d12](https://linux-hardware.org/?probe=5f1abb9d12) | Jul 11, 2022 |
| Apple         | MacBookPro14,1              | [32cbf49371](https://linux-hardware.org/?probe=32cbf49371) | Jul 11, 2022 |
| HP            | EliteBook 840 G5            | [392310b916](https://linux-hardware.org/?probe=392310b916) | Jul 11, 2022 |
| Lenovo        | IdeaPad Yoga 11S 20246      | [d088d6021c](https://linux-hardware.org/?probe=d088d6021c) | Jul 11, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [2ffa772ac9](https://linux-hardware.org/?probe=2ffa772ac9) | Jul 10, 2022 |
| HP            | EliteBook 8540p             | [b161f9e458](https://linux-hardware.org/?probe=b161f9e458) | Jul 10, 2022 |
| Lenovo        | ThinkPad T500 2242CTO       | [47bddb4e10](https://linux-hardware.org/?probe=47bddb4e10) | Jul 10, 2022 |
| Lenovo        | ThinkPad T470s 20HFCTO1W... | [2894597236](https://linux-hardware.org/?probe=2894597236) | Jul 10, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [48aa7eac9f](https://linux-hardware.org/?probe=48aa7eac9f) | Jul 09, 2022 |
| Valve         | Jupiter                     | [98711d54c1](https://linux-hardware.org/?probe=98711d54c1) | Jul 08, 2022 |
| Dell          | Latitude 5290 2-in-1        | [5ecc52d011](https://linux-hardware.org/?probe=5ecc52d011) | Jul 08, 2022 |
| HP            | Pavilion Laptop 15-cs3xx... | [2c457a6e4e](https://linux-hardware.org/?probe=2c457a6e4e) | Jul 07, 2022 |
| ASUSTek       | X553MA                      | [80d9c382cd](https://linux-hardware.org/?probe=80d9c382cd) | Jul 07, 2022 |
| ASUSTek       | X553MA                      | [9082e63d7d](https://linux-hardware.org/?probe=9082e63d7d) | Jul 07, 2022 |
| Lenovo        | ThinkPad T500 2242CTO       | [106199561c](https://linux-hardware.org/?probe=106199561c) | Jul 07, 2022 |
| Acer          | Nitro AN515-53              | [d31c5d1c11](https://linux-hardware.org/?probe=d31c5d1c11) | Jul 06, 2022 |
| Dell          | Latitude 7420               | [219cf18b1e](https://linux-hardware.org/?probe=219cf18b1e) | Jul 06, 2022 |
| Acer          | Nitro AN515-53              | [0304267499](https://linux-hardware.org/?probe=0304267499) | Jul 06, 2022 |
| Google        | Aleena                      | [33110c34a9](https://linux-hardware.org/?probe=33110c34a9) | Jul 06, 2022 |
| HP            | EliteBook 2530p             | [a4b4609db8](https://linux-hardware.org/?probe=a4b4609db8) | Jul 05, 2022 |
| ASUSTek       | G55VW                       | [fa0346f5df](https://linux-hardware.org/?probe=fa0346f5df) | Jul 05, 2022 |
| ASUSTek       | G55VW                       | [832ca8cf45](https://linux-hardware.org/?probe=832ca8cf45) | Jul 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [eb9c212159](https://linux-hardware.org/?probe=eb9c212159) | Jul 04, 2022 |
| ASUSTek       | X541UJ                      | [d3f8e6dee5](https://linux-hardware.org/?probe=d3f8e6dee5) | Jul 04, 2022 |
| Apple         | MacBookPro11,5              | [25e69108df](https://linux-hardware.org/?probe=25e69108df) | Jul 03, 2022 |
| Acer          | Aspire A515-52G             | [8ac3e2bcbc](https://linux-hardware.org/?probe=8ac3e2bcbc) | Jul 02, 2022 |
| Acer          | Aspire 5742Z                | [46f56997be](https://linux-hardware.org/?probe=46f56997be) | Jul 02, 2022 |
| Acer          | Nitro AN517-52              | [3920a80387](https://linux-hardware.org/?probe=3920a80387) | Jul 02, 2022 |
| Acer          | Nitro AN517-52              | [37fbd3a600](https://linux-hardware.org/?probe=37fbd3a600) | Jul 02, 2022 |
| Dell          | Precision 5550              | [0ddb8905e5](https://linux-hardware.org/?probe=0ddb8905e5) | Jul 01, 2022 |
| Dell          | Inspiron 1720               | [bbd0bf2dc0](https://linux-hardware.org/?probe=bbd0bf2dc0) | Jun 30, 2022 |
| ASUSTek       | X553MA                      | [804bbd8147](https://linux-hardware.org/?probe=804bbd8147) | Jun 30, 2022 |
| ASUSTek       | X553MA                      | [9fe936cec8](https://linux-hardware.org/?probe=9fe936cec8) | Jun 30, 2022 |
| Dell          | Inspiron 3531               | [2c8286100d](https://linux-hardware.org/?probe=2c8286100d) | Jun 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [9de675d3d1](https://linux-hardware.org/?probe=9de675d3d1) | Jun 29, 2022 |
| ASUSTek       | G752VT                      | [d51730ccbf](https://linux-hardware.org/?probe=d51730ccbf) | Jun 29, 2022 |
| Dell          | Latitude 5520               | [0504660b50](https://linux-hardware.org/?probe=0504660b50) | Jun 28, 2022 |
| Apple         | MacBookPro10,1              | [a27f696a28](https://linux-hardware.org/?probe=a27f696a28) | Jun 27, 2022 |
| Toshiba       | Satellite A200              | [932496f041](https://linux-hardware.org/?probe=932496f041) | Jun 27, 2022 |
| Lenovo        | ThinkPad T400 6475AT3       | [55fd247328](https://linux-hardware.org/?probe=55fd247328) | Jun 26, 2022 |
| Acer          | Aspire A315-42              | [57d9c7c28a](https://linux-hardware.org/?probe=57d9c7c28a) | Jun 24, 2022 |
| System76      | Darter Pro                  | [db7f217878](https://linux-hardware.org/?probe=db7f217878) | Jun 24, 2022 |
| Toshiba       | Satellite S50-A             | [c2e7c1b26d](https://linux-hardware.org/?probe=c2e7c1b26d) | Jun 24, 2022 |
| Acer          | Nitro AN515-54              | [afce38a95a](https://linux-hardware.org/?probe=afce38a95a) | Jun 24, 2022 |
| Lenovo        | ThinkPad T420 4236J73       | [088ba8b97c](https://linux-hardware.org/?probe=088ba8b97c) | Jun 23, 2022 |
| HP            | Pavilion g6                 | [c4524cb21f](https://linux-hardware.org/?probe=c4524cb21f) | Jun 23, 2022 |
| Dell          | Latitude E6540              | [c0f2801648](https://linux-hardware.org/?probe=c0f2801648) | Jun 21, 2022 |
| Lenovo        | ThinkPad T420 4236EF4       | [1894bb8853](https://linux-hardware.org/?probe=1894bb8853) | Jun 21, 2022 |
| Dell          | Latitude E6540              | [7d19e0b30e](https://linux-hardware.org/?probe=7d19e0b30e) | Jun 20, 2022 |
| Google        | Droid                       | [5a175a2a78](https://linux-hardware.org/?probe=5a175a2a78) | Jun 20, 2022 |
| HP            | Pavilion dv7                | [ab34fbb528](https://linux-hardware.org/?probe=ab34fbb528) | Jun 19, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [4b10fd12ae](https://linux-hardware.org/?probe=4b10fd12ae) | Jun 19, 2022 |
| HP            | Laptop 15-ef0xxx            | [f0cf5e0f30](https://linux-hardware.org/?probe=f0cf5e0f30) | Jun 18, 2022 |
| HP            | Laptop 14-fq0xxx            | [bc61209d78](https://linux-hardware.org/?probe=bc61209d78) | Jun 18, 2022 |
| Dell          | Latitude E6540              | [4806aec13b](https://linux-hardware.org/?probe=4806aec13b) | Jun 16, 2022 |
| Apple         | MacBookPro8,1               | [145a1e77fc](https://linux-hardware.org/?probe=145a1e77fc) | Jun 16, 2022 |
| Lenovo        | Legion 7 15IMH05 81YT       | [cc1947a21b](https://linux-hardware.org/?probe=cc1947a21b) | Jun 15, 2022 |
| Lenovo        | Legion 7 15IMH05 81YT       | [cba78f563c](https://linux-hardware.org/?probe=cba78f563c) | Jun 15, 2022 |
| Apple         | MacBookAir7,2               | [fc34430f8d](https://linux-hardware.org/?probe=fc34430f8d) | Jun 15, 2022 |
| Dell          | Precision 5550              | [f5f815ceed](https://linux-hardware.org/?probe=f5f815ceed) | Jun 14, 2022 |
| HP            | Laptop 14-fq0xxx            | [d7cccd8f1d](https://linux-hardware.org/?probe=d7cccd8f1d) | Jun 14, 2022 |
| GPU Compan... | GWTN141-10                  | [c856f6d54f](https://linux-hardware.org/?probe=c856f6d54f) | Jun 14, 2022 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [aa4ef3154d](https://linux-hardware.org/?probe=aa4ef3154d) | Jun 14, 2022 |
| Notebook      | P65_P67SE                   | [590b7204da](https://linux-hardware.org/?probe=590b7204da) | Jun 13, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [e26e612120](https://linux-hardware.org/?probe=e26e612120) | Jun 13, 2022 |
| HP            | EliteBook 840 G3            | [e18df87b93](https://linux-hardware.org/?probe=e18df87b93) | Jun 13, 2022 |
| HP            | ProBook 470 G4              | [29f73d7f11](https://linux-hardware.org/?probe=29f73d7f11) | Jun 12, 2022 |
| Lenovo        | IdeaPad Slim 7 Carbon 14... | [9382b4e2c0](https://linux-hardware.org/?probe=9382b4e2c0) | Jun 12, 2022 |
| Lenovo        | IdeaPad Slim 7 Carbon 14... | [06526726ca](https://linux-hardware.org/?probe=06526726ca) | Jun 11, 2022 |
| HP            | Pavilion 17                 | [bed3614b80](https://linux-hardware.org/?probe=bed3614b80) | Jun 11, 2022 |
| Razer         | Blade                       | [df8f6881a7](https://linux-hardware.org/?probe=df8f6881a7) | Jun 10, 2022 |
| Dell          | Latitude E5550              | [95baf2f400](https://linux-hardware.org/?probe=95baf2f400) | Jun 10, 2022 |
| ASUSTek       | X541UAK                     | [92a20ee191](https://linux-hardware.org/?probe=92a20ee191) | Jun 08, 2022 |
| Dell          | Latitude E5430 non-vPro     | [ff7b51ffc8](https://linux-hardware.org/?probe=ff7b51ffc8) | Jun 08, 2022 |
| ASUSTek       | G752VT                      | [bb5bb68126](https://linux-hardware.org/?probe=bb5bb68126) | Jun 08, 2022 |
| Google        | Cave                        | [16183f9a77](https://linux-hardware.org/?probe=16183f9a77) | Jun 07, 2022 |
| Toshiba       | Satellite L850              | [809d0bbd73](https://linux-hardware.org/?probe=809d0bbd73) | Jun 07, 2022 |
| Toshiba       | Satellite L850              | [761d37bd31](https://linux-hardware.org/?probe=761d37bd31) | Jun 06, 2022 |
| HP            | Laptop 14-fq0xxx            | [d88feaaf5e](https://linux-hardware.org/?probe=d88feaaf5e) | Jun 06, 2022 |
| System76      | Oryx Pro                    | [ec0e78e0f6](https://linux-hardware.org/?probe=ec0e78e0f6) | Jun 06, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [fffae020ba](https://linux-hardware.org/?probe=fffae020ba) | Jun 06, 2022 |
| HP            | Laptop 14-fq0xxx            | [3ebcdc19fa](https://linux-hardware.org/?probe=3ebcdc19fa) | Jun 04, 2022 |
| MSI           | GP72 6QF                    | [4f62904f80](https://linux-hardware.org/?probe=4f62904f80) | Jun 04, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IV... | [cae8761200](https://linux-hardware.org/?probe=cae8761200) | Jun 03, 2022 |
| ASUSTek       | ROG Strix G733ZX_G733ZX     | [dca80e1df5](https://linux-hardware.org/?probe=dca80e1df5) | Jun 02, 2022 |
| Dell          | Latitude 7420               | [5be44c8aae](https://linux-hardware.org/?probe=5be44c8aae) | Jun 01, 2022 |
| Lenovo        | Edge 15 80K9                | [5c8bb97759](https://linux-hardware.org/?probe=5c8bb97759) | Jun 01, 2022 |
| Lenovo        | Edge 15 80K9                | [9bbdfc95bb](https://linux-hardware.org/?probe=9bbdfc95bb) | May 31, 2022 |
| ASUSTek       | G73Jh                       | [b7db998ac4](https://linux-hardware.org/?probe=b7db998ac4) | May 31, 2022 |
| Apple         | MacBookAir4,1               | [a0b4c18cd0](https://linux-hardware.org/?probe=a0b4c18cd0) | May 31, 2022 |
| Lenovo        | Edge 15 80K9                | [586a31368f](https://linux-hardware.org/?probe=586a31368f) | May 30, 2022 |
| HP            | Stream Laptop 11-ak1xxx     | [2d2044b499](https://linux-hardware.org/?probe=2d2044b499) | May 30, 2022 |
| Dell          | Latitude 5289               | [f9e3e0fa57](https://linux-hardware.org/?probe=f9e3e0fa57) | May 30, 2022 |
| Dell          | Studio XPS 1645             | [5fdf8e3100](https://linux-hardware.org/?probe=5fdf8e3100) | May 29, 2022 |
| Dell          | XPS 13 9343                 | [5881b6ea1b](https://linux-hardware.org/?probe=5881b6ea1b) | May 28, 2022 |
| ASUSTek       | Strix 17 GL703GE            | [5d5ba64239](https://linux-hardware.org/?probe=5d5ba64239) | May 28, 2022 |
| Dell          | Inspiron 5521               | [84cc31cb32](https://linux-hardware.org/?probe=84cc31cb32) | May 27, 2022 |
| Lenovo        | Legion 7 15IMH05 81YT       | [602f942afc](https://linux-hardware.org/?probe=602f942afc) | May 27, 2022 |
| Lenovo        | Legion 7 15IMH05 81YT       | [a7cb65fb76](https://linux-hardware.org/?probe=a7cb65fb76) | May 27, 2022 |
| Dell          | Inspiron 15 5510            | [641c79318b](https://linux-hardware.org/?probe=641c79318b) | May 27, 2022 |
| Dell          | Latitude D630               | [0560d4c462](https://linux-hardware.org/?probe=0560d4c462) | May 27, 2022 |
| Valve         | Jupiter                     | [43f315aa0c](https://linux-hardware.org/?probe=43f315aa0c) | May 27, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [9b4287fa8b](https://linux-hardware.org/?probe=9b4287fa8b) | May 26, 2022 |
| Dell          | G15 5515                    | [4f47780467](https://linux-hardware.org/?probe=4f47780467) | May 26, 2022 |
| Acer          | Swift SF314-42              | [42577fc274](https://linux-hardware.org/?probe=42577fc274) | May 26, 2022 |
| Acer          | Swift SF314-42              | [08f7af683d](https://linux-hardware.org/?probe=08f7af683d) | May 26, 2022 |
| Dell          | Latitude E6420              | [425a9e4f0d](https://linux-hardware.org/?probe=425a9e4f0d) | May 26, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [75063d8f18](https://linux-hardware.org/?probe=75063d8f18) | May 26, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [0d1ba4ee73](https://linux-hardware.org/?probe=0d1ba4ee73) | May 26, 2022 |
| HP            | Laptop 15-ef0xxx            | [a214740f99](https://linux-hardware.org/?probe=a214740f99) | May 25, 2022 |
| A-DATA Tec... | XENIA 15                    | [1d7941d921](https://linux-hardware.org/?probe=1d7941d921) | May 25, 2022 |
| Dell          | Precision 5550              | [6b17026494](https://linux-hardware.org/?probe=6b17026494) | May 24, 2022 |
| Dell          | Latitude D830               | [f2f09cee8c](https://linux-hardware.org/?probe=f2f09cee8c) | May 24, 2022 |
| Dell          | Latitude E5450              | [7d23576abb](https://linux-hardware.org/?probe=7d23576abb) | May 23, 2022 |
| Dell          | Latitude E5450              | [f0c746ba9e](https://linux-hardware.org/?probe=f0c746ba9e) | May 23, 2022 |
| Dell          | XPS 13 9310                 | [c7cf536a61](https://linux-hardware.org/?probe=c7cf536a61) | May 23, 2022 |
| Alienware     | m15 Ryzen Ed. R5            | [f451e1b307](https://linux-hardware.org/?probe=f451e1b307) | May 22, 2022 |
| Lenovo        | ThinkPad W520 42763JF       | [2b87bae835](https://linux-hardware.org/?probe=2b87bae835) | May 22, 2022 |
| Unknown       | Unknown                     | [261a0bf179](https://linux-hardware.org/?probe=261a0bf179) | May 21, 2022 |
| Dell          | XPS 13 9310                 | [06943bb7f1](https://linux-hardware.org/?probe=06943bb7f1) | May 21, 2022 |
| HP            | Notebook                    | [7e7b774d40](https://linux-hardware.org/?probe=7e7b774d40) | May 21, 2022 |
| MSI           | MS-7A34                     | [8956078328](https://linux-hardware.org/?probe=8956078328) | May 21, 2022 |
| MSI           | Stealth GS66 12UE           | [98bccdf1f2](https://linux-hardware.org/?probe=98bccdf1f2) | May 20, 2022 |
| Dell          | Inspiron 5565               | [a583bbdc35](https://linux-hardware.org/?probe=a583bbdc35) | May 19, 2022 |
| Dell          | XPS 15 9510                 | [ee62ecda2e](https://linux-hardware.org/?probe=ee62ecda2e) | May 19, 2022 |
| Dell          | Latitude 5430 Rugged        | [c32e65738e](https://linux-hardware.org/?probe=c32e65738e) | May 18, 2022 |
| Dell          | Inspiron 5593               | [e08308603a](https://linux-hardware.org/?probe=e08308603a) | May 18, 2022 |
| HP            | Pavilion g4                 | [dcb7b65b12](https://linux-hardware.org/?probe=dcb7b65b12) | May 18, 2022 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [9ff24e3f8b](https://linux-hardware.org/?probe=9ff24e3f8b) | May 18, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [716443586f](https://linux-hardware.org/?probe=716443586f) | May 18, 2022 |
| Acer          | Aspire 5250                 | [7ca9e60266](https://linux-hardware.org/?probe=7ca9e60266) | May 17, 2022 |
| Dell          | XPS 13 9370                 | [6459eab7e8](https://linux-hardware.org/?probe=6459eab7e8) | May 17, 2022 |
| Acer          | Aspire 5810T                | [1cf713e3df](https://linux-hardware.org/?probe=1cf713e3df) | May 16, 2022 |
| Alienware     | x17 R2                      | [b755419e26](https://linux-hardware.org/?probe=b755419e26) | May 16, 2022 |
| Apple         | MacBookAir4,1               | [c4773713e6](https://linux-hardware.org/?probe=c4773713e6) | May 16, 2022 |
| Apple         | MacBookAir4,1               | [928416ecd0](https://linux-hardware.org/?probe=928416ecd0) | May 16, 2022 |
| Google        | Terra                       | [35088c1c05](https://linux-hardware.org/?probe=35088c1c05) | May 16, 2022 |
| HP            | Laptop 15-bs0xx             | [9445ab07bf](https://linux-hardware.org/?probe=9445ab07bf) | May 15, 2022 |
| Unknown       | Unknown                     | [1243a1c63a](https://linux-hardware.org/?probe=1243a1c63a) | May 15, 2022 |
| Dell          | XPS 15 9510                 | [653725bdde](https://linux-hardware.org/?probe=653725bdde) | May 15, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [0f4e4f3887](https://linux-hardware.org/?probe=0f4e4f3887) | May 14, 2022 |
| Acer          | Predator G9-593             | [ab4bc72022](https://linux-hardware.org/?probe=ab4bc72022) | May 14, 2022 |
| Dell          | Latitude E6400              | [2831bacde3](https://linux-hardware.org/?probe=2831bacde3) | May 13, 2022 |
| ASUSTek       | X551MA                      | [6a39b7b0da](https://linux-hardware.org/?probe=6a39b7b0da) | May 13, 2022 |
| ASUSTek       | Strix 17 GL703GE            | [cfff0d1922](https://linux-hardware.org/?probe=cfff0d1922) | May 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [24d4683d52](https://linux-hardware.org/?probe=24d4683d52) | May 13, 2022 |
| Dell          | Latitude D830               | [d19fc99d54](https://linux-hardware.org/?probe=d19fc99d54) | May 12, 2022 |
| Dell          | XPS 15 9510                 | [299f811f98](https://linux-hardware.org/?probe=299f811f98) | May 12, 2022 |
| ASUSTek       | X541UAK                     | [50747765ef](https://linux-hardware.org/?probe=50747765ef) | May 10, 2022 |
| MSI           | GF75 Thin 9SC               | [6e8c40ad7c](https://linux-hardware.org/?probe=6e8c40ad7c) | May 10, 2022 |
| ASUSTek       | X541UAK                     | [c1c837e821](https://linux-hardware.org/?probe=c1c837e821) | May 10, 2022 |
| ASUSTek       | X200CA                      | [e041ed14b2](https://linux-hardware.org/?probe=e041ed14b2) | May 10, 2022 |
| HP            | ZBook 15 G3                 | [82bbcd17e8](https://linux-hardware.org/?probe=82bbcd17e8) | May 10, 2022 |
| Toshiba       | Satellite L655              | [d31e2badae](https://linux-hardware.org/?probe=d31e2badae) | May 09, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [48678afa40](https://linux-hardware.org/?probe=48678afa40) | May 09, 2022 |
| Lenovo        | ThinkPad X131e 33691J6      | [1f492cb261](https://linux-hardware.org/?probe=1f492cb261) | May 08, 2022 |
| ASUSTek       | X200CA                      | [bed44df427](https://linux-hardware.org/?probe=bed44df427) | May 07, 2022 |
| Acer          | Aspire 5810T                | [8d9b944789](https://linux-hardware.org/?probe=8d9b944789) | May 07, 2022 |
| Lenovo        | ThinkPad T460s 20FAS0F40... | [9d6a8926ec](https://linux-hardware.org/?probe=9d6a8926ec) | May 06, 2022 |
| Lenovo        | ThinkPad T440p 20AN00DEU... | [b13325e763](https://linux-hardware.org/?probe=b13325e763) | May 06, 2022 |
| Apple         | MacBookPro11,2              | [0af35aa835](https://linux-hardware.org/?probe=0af35aa835) | May 06, 2022 |
| Toshiba       | Satellite C670D             | [3eedd8ce6b](https://linux-hardware.org/?probe=3eedd8ce6b) | May 05, 2022 |
| Acer          | TravelMate P653-M           | [221d943970](https://linux-hardware.org/?probe=221d943970) | May 04, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [d861de9453](https://linux-hardware.org/?probe=d861de9453) | May 04, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [6b9d36debb](https://linux-hardware.org/?probe=6b9d36debb) | May 04, 2022 |
| Alienware     | m15 R4                      | [3b09d65e13](https://linux-hardware.org/?probe=3b09d65e13) | May 04, 2022 |
| Dell          | Vostro 3500                 | [00add28269](https://linux-hardware.org/?probe=00add28269) | May 03, 2022 |
| Alienware     | m15 R4                      | [1f5f3048d6](https://linux-hardware.org/?probe=1f5f3048d6) | May 03, 2022 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | [90aa5187ab](https://linux-hardware.org/?probe=90aa5187ab) | May 02, 2022 |
| MSI           | GS65 Stealth 8SG            | [05f80b3e70](https://linux-hardware.org/?probe=05f80b3e70) | May 02, 2022 |
| Dell          | Latitude E6540              | [ad5bf6fab1](https://linux-hardware.org/?probe=ad5bf6fab1) | May 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [6710b89c52](https://linux-hardware.org/?probe=6710b89c52) | Apr 30, 2022 |
| Lenovo        | ThinkPad Edge E530 62724... | [07334ae084](https://linux-hardware.org/?probe=07334ae084) | Apr 30, 2022 |
| ASUSTek       | G55VW                       | [6bd8a1b04a](https://linux-hardware.org/?probe=6bd8a1b04a) | Apr 29, 2022 |
| ASUSTek       | X541UAK                     | [7bac9962d9](https://linux-hardware.org/?probe=7bac9962d9) | Apr 29, 2022 |
| Acer          | Swift SF314-57              | [d48d0527ee](https://linux-hardware.org/?probe=d48d0527ee) | Apr 28, 2022 |
| Dell          | XPS 15 9560                 | [92e903308e](https://linux-hardware.org/?probe=92e903308e) | Apr 27, 2022 |
| System76      | Pangolin                    | [d326fc9a39](https://linux-hardware.org/?probe=d326fc9a39) | Apr 27, 2022 |
| HP            | Unknown                     | [32f3c98619](https://linux-hardware.org/?probe=32f3c98619) | Apr 27, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [ff8e46a260](https://linux-hardware.org/?probe=ff8e46a260) | Apr 27, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [0a6534997e](https://linux-hardware.org/?probe=0a6534997e) | Apr 27, 2022 |
| Lenovo        | Legion 7 15IMH05 81YT       | [9384c00f6e](https://linux-hardware.org/?probe=9384c00f6e) | Apr 26, 2022 |
| Acer          | Aspire ES1-523              | [23c9792994](https://linux-hardware.org/?probe=23c9792994) | Apr 25, 2022 |
| HP            | EliteBook 830 G5            | [17f9b4e988](https://linux-hardware.org/?probe=17f9b4e988) | Apr 25, 2022 |
| Dell          | Latitude D830               | [1c23417a15](https://linux-hardware.org/?probe=1c23417a15) | Apr 25, 2022 |
| Acer          | Nitro AN515-55              | [04b51fe1cf](https://linux-hardware.org/?probe=04b51fe1cf) | Apr 25, 2022 |
| HUAWEI        | MACH-WX9                    | [0199a1bcec](https://linux-hardware.org/?probe=0199a1bcec) | Apr 24, 2022 |
| MSI           | GP72 6QF                    | [8a2ac9964c](https://linux-hardware.org/?probe=8a2ac9964c) | Apr 24, 2022 |
| Alienware     | m15 R7                      | [77727a1731](https://linux-hardware.org/?probe=77727a1731) | Apr 24, 2022 |
| ASUSTek       | K55A                        | [079c627411](https://linux-hardware.org/?probe=079c627411) | Apr 24, 2022 |
| Dell          | Vostro 3500                 | [33a9b533e8](https://linux-hardware.org/?probe=33a9b533e8) | Apr 23, 2022 |
| Dell          | Vostro 3500                 | [ffb0508bd2](https://linux-hardware.org/?probe=ffb0508bd2) | Apr 23, 2022 |
| HP            | EliteBook 8470p             | [0ee15f97fd](https://linux-hardware.org/?probe=0ee15f97fd) | Apr 23, 2022 |
| Apple         | MacBookPro6,1               | [e73885a94d](https://linux-hardware.org/?probe=e73885a94d) | Apr 23, 2022 |
| Mediacom      | GTZS                        | [41939828a4](https://linux-hardware.org/?probe=41939828a4) | Apr 23, 2022 |
| Dell          | XPS 15 7590                 | [f2680af572](https://linux-hardware.org/?probe=f2680af572) | Apr 22, 2022 |
| HP            | EliteBook 830 G5            | [6061f1cd1e](https://linux-hardware.org/?probe=6061f1cd1e) | Apr 22, 2022 |
| Unknown       | Unknown                     | [dad86f3306](https://linux-hardware.org/?probe=dad86f3306) | Apr 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [58e0a1814b](https://linux-hardware.org/?probe=58e0a1814b) | Apr 21, 2022 |
| Mediacom      | GTZS                        | [edc22ef82a](https://linux-hardware.org/?probe=edc22ef82a) | Apr 21, 2022 |
| Lenovo        | ThinkPad X200 Tablet 744... | [1945aa754f](https://linux-hardware.org/?probe=1945aa754f) | Apr 20, 2022 |
| Lenovo        | ThinkPad T450s 20BWS19E0... | [c6a1ec3df0](https://linux-hardware.org/?probe=c6a1ec3df0) | Apr 20, 2022 |
| HP            | ENVY Laptop 15-ep1xxx       | [29f92aa75f](https://linux-hardware.org/?probe=29f92aa75f) | Apr 19, 2022 |
| HP            | Laptop 15-dw0xxx            | [7f35172610](https://linux-hardware.org/?probe=7f35172610) | Apr 19, 2022 |
| Dell          | Inspiron 15-3567            | [f8e7d70919](https://linux-hardware.org/?probe=f8e7d70919) | Apr 18, 2022 |
| HP            | ProBook 4535s               | [23ab986b5e](https://linux-hardware.org/?probe=23ab986b5e) | Apr 18, 2022 |
| HP            | Pavilion dv4                | [7bd955f313](https://linux-hardware.org/?probe=7bd955f313) | Apr 18, 2022 |
| Acer          | Aspire V3-571               | [b1ea72b76e](https://linux-hardware.org/?probe=b1ea72b76e) | Apr 18, 2022 |
| Lenovo        | G50-80 80E5                 | [a07c515f60](https://linux-hardware.org/?probe=a07c515f60) | Apr 17, 2022 |
| Dell          | Latitude E6410              | [391866815a](https://linux-hardware.org/?probe=391866815a) | Apr 17, 2022 |
| ASUSTek       | PU401LAC                    | [08a76b8cb8](https://linux-hardware.org/?probe=08a76b8cb8) | Apr 17, 2022 |
| ASUSTek       | K53Z                        | [2d870acfa1](https://linux-hardware.org/?probe=2d870acfa1) | Apr 16, 2022 |
| Lenovo        | ThinkPad E520 11433BU       | [eb10b5f739](https://linux-hardware.org/?probe=eb10b5f739) | Apr 16, 2022 |
| Dell          | Latitude E6430              | [c9a365bfe3](https://linux-hardware.org/?probe=c9a365bfe3) | Apr 16, 2022 |
| Dell          | XPS 15 9560                 | [c540449ce7](https://linux-hardware.org/?probe=c540449ce7) | Apr 16, 2022 |
| Dell          | Latitude E6430              | [fc7e6fce7b](https://linux-hardware.org/?probe=fc7e6fce7b) | Apr 15, 2022 |
| Dell          | Latitude E7250              | [532fb04297](https://linux-hardware.org/?probe=532fb04297) | Apr 15, 2022 |
| HP            | Laptop 14-cf0xxx            | [3fcf4f7e02](https://linux-hardware.org/?probe=3fcf4f7e02) | Apr 14, 2022 |
| Acer          | Swift SF314-42              | [85d345a867](https://linux-hardware.org/?probe=85d345a867) | Apr 14, 2022 |
| Dell          | Latitude E7250              | [a1e63550ab](https://linux-hardware.org/?probe=a1e63550ab) | Apr 14, 2022 |
| Lenovo        | ThinkPad P53 20QNS00Y00     | [5ef7e630fa](https://linux-hardware.org/?probe=5ef7e630fa) | Apr 14, 2022 |
| Lenovo        | ThinkPad P70 20ERCTO1WW     | [d8a70fe32c](https://linux-hardware.org/?probe=d8a70fe32c) | Apr 13, 2022 |
| System76      | Oryx Pro                    | [8521355f49](https://linux-hardware.org/?probe=8521355f49) | Apr 13, 2022 |
| Lenovo        | ThinkPad P53s 20N6CTO1WW    | [3b06e810bc](https://linux-hardware.org/?probe=3b06e810bc) | Apr 13, 2022 |
| Dell          | XPS 15 9500                 | [b64e82a4a6](https://linux-hardware.org/?probe=b64e82a4a6) | Apr 13, 2022 |
| Dell          | Inspiron 7570               | [8d68856bad](https://linux-hardware.org/?probe=8d68856bad) | Apr 13, 2022 |
| Acer          | Aspire A715-74G             | [9f5a2049e3](https://linux-hardware.org/?probe=9f5a2049e3) | Apr 13, 2022 |
| Acer          | Swift SF314-42              | [fe3ebf82b0](https://linux-hardware.org/?probe=fe3ebf82b0) | Apr 13, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [d42f43dc69](https://linux-hardware.org/?probe=d42f43dc69) | Apr 13, 2022 |
| Dell          | Inspiron 5577               | [d82fa1bfc9](https://linux-hardware.org/?probe=d82fa1bfc9) | Apr 13, 2022 |
| Acer          | Aspire R3-131T              | [44a4c66cfe](https://linux-hardware.org/?probe=44a4c66cfe) | Apr 13, 2022 |
| Dell          | XPS 15 7590                 | [d90283da2d](https://linux-hardware.org/?probe=d90283da2d) | Apr 13, 2022 |
| HP            | ProBook 4535s               | [1aa29ed37f](https://linux-hardware.org/?probe=1aa29ed37f) | Apr 13, 2022 |
| Panasonic     | CF-31SBLJGDM                | [60a1068658](https://linux-hardware.org/?probe=60a1068658) | Apr 13, 2022 |
| ASUSTek       | ZenBook UX434FL_UX434FL     | [a07d8cec5b](https://linux-hardware.org/?probe=a07d8cec5b) | Apr 13, 2022 |
| Lenovo        | IdeaPad Y550 4186           | [0ba7d3b80a](https://linux-hardware.org/?probe=0ba7d3b80a) | Apr 13, 2022 |
| Dell          | Latitude D830               | [54233652ca](https://linux-hardware.org/?probe=54233652ca) | Apr 12, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [0507e6395b](https://linux-hardware.org/?probe=0507e6395b) | Apr 11, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IV... | [0def0def83](https://linux-hardware.org/?probe=0def0def83) | Apr 09, 2022 |
| ASUSTek       | GL502VT                     | [bbad575f6a](https://linux-hardware.org/?probe=bbad575f6a) | Apr 08, 2022 |
| Dell          | Latitude E5500              | [485521f38b](https://linux-hardware.org/?probe=485521f38b) | Apr 08, 2022 |
| HP            | Victus by Laptop 16-d0xx... | [3c3e8b3ae2](https://linux-hardware.org/?probe=3c3e8b3ae2) | Apr 07, 2022 |
| Lenovo        | ThinkPad E485 20KUCTO1WW    | [8dae5ce312](https://linux-hardware.org/?probe=8dae5ce312) | Apr 07, 2022 |
| RCA           | WT9503W003                  | [e661ebe9b4](https://linux-hardware.org/?probe=e661ebe9b4) | Apr 07, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | [158e261517](https://linux-hardware.org/?probe=158e261517) | Apr 07, 2022 |
| HP            | 2000                        | [e4610bcc0e](https://linux-hardware.org/?probe=e4610bcc0e) | Apr 07, 2022 |
| Dell          | Precision M4700             | [ab99532bd5](https://linux-hardware.org/?probe=ab99532bd5) | Apr 04, 2022 |
| Toshiba       | Satellite L655              | [ac8c92d2c4](https://linux-hardware.org/?probe=ac8c92d2c4) | Apr 03, 2022 |
| HP            | EliteBook 8770w             | [e826deade2](https://linux-hardware.org/?probe=e826deade2) | Apr 03, 2022 |
| Lenovo        | ThinkPad L430 2465D16       | [411bc7237f](https://linux-hardware.org/?probe=411bc7237f) | Apr 03, 2022 |
| ASUSTek       | X555QA                      | [d23dae873a](https://linux-hardware.org/?probe=d23dae873a) | Apr 02, 2022 |
| ASUSTek       | ROG Strix G513QC_G513QC     | [697f820432](https://linux-hardware.org/?probe=697f820432) | Apr 02, 2022 |
| Lenovo        | IdeaPad 110-15AST 80TR      | [fec94b0f90](https://linux-hardware.org/?probe=fec94b0f90) | Apr 02, 2022 |
| Acer          | Aspire 5735                 | [9e91d55a6d](https://linux-hardware.org/?probe=9e91d55a6d) | Apr 01, 2022 |
| Dell          | Inspiron 5515               | [224f954e8f](https://linux-hardware.org/?probe=224f954e8f) | Apr 01, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | [8b613eb0c8](https://linux-hardware.org/?probe=8b613eb0c8) | Apr 01, 2022 |
| Dell          | Latitude 6430U              | [5a17c91b91](https://linux-hardware.org/?probe=5a17c91b91) | Mar 31, 2022 |
| HP            | Pavilion Notebook           | [a18360bae8](https://linux-hardware.org/?probe=a18360bae8) | Mar 31, 2022 |
| Acer          | Aspire ES1-531              | [e617f1e49b](https://linux-hardware.org/?probe=e617f1e49b) | Mar 30, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [0f18e7b54b](https://linux-hardware.org/?probe=0f18e7b54b) | Mar 30, 2022 |
| Getac         | B300G5                      | [9a1ef08d85](https://linux-hardware.org/?probe=9a1ef08d85) | Mar 30, 2022 |
| Dell          | Inspiron 1764               | [6eb66d942d](https://linux-hardware.org/?probe=6eb66d942d) | Mar 29, 2022 |
| Dell          | Latitude E5550              | [f01dc93afc](https://linux-hardware.org/?probe=f01dc93afc) | Mar 28, 2022 |
| Panasonic     | CF-31ACJAXPM                | [c90a918208](https://linux-hardware.org/?probe=c90a918208) | Mar 28, 2022 |
| Acer          | Aspire E5-771G              | [a765f92826](https://linux-hardware.org/?probe=a765f92826) | Mar 28, 2022 |
| HP            | Pavilion Notebook           | [ac807c9324](https://linux-hardware.org/?probe=ac807c9324) | Mar 27, 2022 |
| HP            | Laptop 15-db0xxx            | [062232ca4f](https://linux-hardware.org/?probe=062232ca4f) | Mar 27, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | [8392d5c3fe](https://linux-hardware.org/?probe=8392d5c3fe) | Mar 27, 2022 |
| Acer          | Aspire E1-472               | [e2a4e96dff](https://linux-hardware.org/?probe=e2a4e96dff) | Mar 27, 2022 |
| HP            | EliteBook 8770w             | [3d5b596cf4](https://linux-hardware.org/?probe=3d5b596cf4) | Mar 27, 2022 |
| ASUSTek       | N550JK                      | [145b778642](https://linux-hardware.org/?probe=145b778642) | Mar 26, 2022 |
| Insyde        | GeminiLake                  | [44967ed898](https://linux-hardware.org/?probe=44967ed898) | Mar 26, 2022 |
| Dell          | XPS 15 9510                 | [e463ecc7bc](https://linux-hardware.org/?probe=e463ecc7bc) | Mar 25, 2022 |
| MSI           | Stealth GS66 12UHS          | [4a6b3d619c](https://linux-hardware.org/?probe=4a6b3d619c) | Mar 25, 2022 |
| MSI           | Stealth GS66 12UHS          | [7d1fa138d0](https://linux-hardware.org/?probe=7d1fa138d0) | Mar 25, 2022 |
| Dell          | Precision M4400             | [5172327d82](https://linux-hardware.org/?probe=5172327d82) | Mar 25, 2022 |
| Unknown       | Apple MacBook Pro (13-in... | [ffde46b23c](https://linux-hardware.org/?probe=ffde46b23c) | Mar 24, 2022 |
| HP            | Pavilion TS Sleekbook 14    | [73c4a3b7b4](https://linux-hardware.org/?probe=73c4a3b7b4) | Mar 24, 2022 |
| HP            | Laptop 15-dy3xxx            | [a3e561b9bc](https://linux-hardware.org/?probe=a3e561b9bc) | Mar 24, 2022 |
| ASUSTek       | X540LA                      | [835286b855](https://linux-hardware.org/?probe=835286b855) | Mar 24, 2022 |
| Razer         | Blade 15 Advanced Model ... | [cb089466a3](https://linux-hardware.org/?probe=cb089466a3) | Mar 24, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | [921004463e](https://linux-hardware.org/?probe=921004463e) | Mar 23, 2022 |
| HP            | Pavilion Notebook           | [e02916c256](https://linux-hardware.org/?probe=e02916c256) | Mar 22, 2022 |
| MSI           | GP62 7RD                    | [edc0dd3639](https://linux-hardware.org/?probe=edc0dd3639) | Mar 22, 2022 |
| HP            | EliteBook 8540p             | [15a215fc17](https://linux-hardware.org/?probe=15a215fc17) | Mar 22, 2022 |
| HP            | EliteBook 8540p             | [f0915a2702](https://linux-hardware.org/?probe=f0915a2702) | Mar 22, 2022 |
| Dell          | XPS 15 9560                 | [86e612cd90](https://linux-hardware.org/?probe=86e612cd90) | Mar 22, 2022 |
| ASUSTek       | N550JK                      | [c759bc20a2](https://linux-hardware.org/?probe=c759bc20a2) | Mar 21, 2022 |
| Dell          | Precision 5560              | [895a6cb7f9](https://linux-hardware.org/?probe=895a6cb7f9) | Mar 21, 2022 |
| Apple         | MacBookPro5,5               | [1570699278](https://linux-hardware.org/?probe=1570699278) | Mar 19, 2022 |
| Toshiba       | Satellite L755              | [89aee4e055](https://linux-hardware.org/?probe=89aee4e055) | Mar 19, 2022 |
| Unknown       | Apple MacBook Pro (13-in... | [d9ba393438](https://linux-hardware.org/?probe=d9ba393438) | Mar 19, 2022 |
| Dell          | Inspiron 5502               | [ce6b8e3716](https://linux-hardware.org/?probe=ce6b8e3716) | Mar 19, 2022 |
| Dell          | XPS 15 9560                 | [a7425250b2](https://linux-hardware.org/?probe=a7425250b2) | Mar 19, 2022 |
| ASUSTek       | G752VT                      | [632814d6a3](https://linux-hardware.org/?probe=632814d6a3) | Mar 18, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | [7e64ef177c](https://linux-hardware.org/?probe=7e64ef177c) | Mar 18, 2022 |
| HP            | Laptop 15-bw0xx             | [e9ebe9f2cd](https://linux-hardware.org/?probe=e9ebe9f2cd) | Mar 18, 2022 |
| HP            | Laptop 15-bw0xx             | [959aaa3f2d](https://linux-hardware.org/?probe=959aaa3f2d) | Mar 18, 2022 |
| MSI           | MS-7A34                     | [27f8a2eb1f](https://linux-hardware.org/?probe=27f8a2eb1f) | Mar 18, 2022 |
| Dell          | Inspiron 5502               | [b5aeb18001](https://linux-hardware.org/?probe=b5aeb18001) | Mar 17, 2022 |
| Dell          | Latitude 5480               | [9ba5463bf9](https://linux-hardware.org/?probe=9ba5463bf9) | Mar 17, 2022 |
| MSI           | GS66 Stealth 10SE           | [fb8d2216a5](https://linux-hardware.org/?probe=fb8d2216a5) | Mar 17, 2022 |
| Lenovo        | ThinkPad E485 20KUCTO1WW    | [d49f3c26e1](https://linux-hardware.org/?probe=d49f3c26e1) | Mar 16, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | [d742a1c2fa](https://linux-hardware.org/?probe=d742a1c2fa) | Mar 16, 2022 |
| Lenovo        | ThinkPad T580 20LAS09100    | [4ee1528efc](https://linux-hardware.org/?probe=4ee1528efc) | Mar 15, 2022 |
| HP            | ProBook 455 G7              | [453d423ede](https://linux-hardware.org/?probe=453d423ede) | Mar 15, 2022 |
| HP            | Laptop 15-dy3xxx            | [181a27f454](https://linux-hardware.org/?probe=181a27f454) | Mar 15, 2022 |
| Dell          | Inspiron 1545               | [461f90d3a5](https://linux-hardware.org/?probe=461f90d3a5) | Mar 14, 2022 |
| HP            | EliteBook Folio 9480m       | [865bf7a50e](https://linux-hardware.org/?probe=865bf7a50e) | Mar 14, 2022 |
| Dell          | Inspiron 7520               | [b9811a6b86](https://linux-hardware.org/?probe=b9811a6b86) | Mar 13, 2022 |
| Dell          | Inspiron 7520               | [09dd135092](https://linux-hardware.org/?probe=09dd135092) | Mar 13, 2022 |
| Lenovo        | 3000 N200 0769ALU           | [f30edee226](https://linux-hardware.org/?probe=f30edee226) | Mar 13, 2022 |
| Apple         | MacBookPro16,1              | [9cce5830b5](https://linux-hardware.org/?probe=9cce5830b5) | Mar 13, 2022 |
| ASUSTek       | X550LC                      | [cb90a1c509](https://linux-hardware.org/?probe=cb90a1c509) | Mar 13, 2022 |
| Lenovo        | ThinkPad W530 24472SU       | [7f42b4a6d9](https://linux-hardware.org/?probe=7f42b4a6d9) | Mar 13, 2022 |
| HP            | EliteBook 840 G4            | [271be85bac](https://linux-hardware.org/?probe=271be85bac) | Mar 12, 2022 |
| HP            | EliteBook 840 G4            | [285fceb14a](https://linux-hardware.org/?probe=285fceb14a) | Mar 12, 2022 |
| Acer          | Swift SF314-42              | [1ff677c35a](https://linux-hardware.org/?probe=1ff677c35a) | Mar 12, 2022 |
| Acer          | Aspire 5742                 | [e840bed876](https://linux-hardware.org/?probe=e840bed876) | Mar 12, 2022 |
| HP            | ZBook 15u G4                | [bcc68d38a4](https://linux-hardware.org/?probe=bcc68d38a4) | Mar 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [f0c0038ae3](https://linux-hardware.org/?probe=f0c0038ae3) | Mar 11, 2022 |
| HP            | ProBook 6470b               | [fbc726a0b8](https://linux-hardware.org/?probe=fbc726a0b8) | Mar 11, 2022 |
| Apple         | MacBookAir6,2               | [92f34786b4](https://linux-hardware.org/?probe=92f34786b4) | Mar 10, 2022 |
| Lenovo        | ThinkPad T430 2347H76       | [493f378237](https://linux-hardware.org/?probe=493f378237) | Mar 10, 2022 |
| HP            | EliteBook Folio 9480m       | [354c365696](https://linux-hardware.org/?probe=354c365696) | Mar 10, 2022 |
| Acer          | Swift SF314-42              | [b8d6b520a5](https://linux-hardware.org/?probe=b8d6b520a5) | Mar 08, 2022 |
| Acer          | Swift SF314-42              | [ee29c46e67](https://linux-hardware.org/?probe=ee29c46e67) | Mar 08, 2022 |
| Dell          | System XPS L702X            | [bc9ab1100f](https://linux-hardware.org/?probe=bc9ab1100f) | Mar 08, 2022 |
| Dell          | System XPS L702X            | [3ac888a340](https://linux-hardware.org/?probe=3ac888a340) | Mar 08, 2022 |
| ASUSTek       | X550LC                      | [97f4cf8c40](https://linux-hardware.org/?probe=97f4cf8c40) | Mar 06, 2022 |
| Toshiba       | Satellite C70D-A            | [c7dfd52f76](https://linux-hardware.org/?probe=c7dfd52f76) | Mar 05, 2022 |
| Acer          | Aspire 5742                 | [c039f0a68d](https://linux-hardware.org/?probe=c039f0a68d) | Mar 05, 2022 |
| Acer          | Aspire 5742                 | [ec7b25958d](https://linux-hardware.org/?probe=ec7b25958d) | Mar 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [3e2bee1e62](https://linux-hardware.org/?probe=3e2bee1e62) | Mar 04, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [3a12accc7d](https://linux-hardware.org/?probe=3a12accc7d) | Mar 03, 2022 |
| Lenovo        | G560 0679                   | [07bbbdef41](https://linux-hardware.org/?probe=07bbbdef41) | Mar 03, 2022 |
| HP            | EliteBook Folio 9480m       | [7683d10ccf](https://linux-hardware.org/?probe=7683d10ccf) | Mar 03, 2022 |
| Dell          | Inspiron 5566               | [9b5ba1cd95](https://linux-hardware.org/?probe=9b5ba1cd95) | Mar 02, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | [59b0615e74](https://linux-hardware.org/?probe=59b0615e74) | Mar 02, 2022 |
| Getac         | B300G5                      | [d782bea38a](https://linux-hardware.org/?probe=d782bea38a) | Mar 02, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [fb9f8e44d0](https://linux-hardware.org/?probe=fb9f8e44d0) | Mar 01, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [46271114d7](https://linux-hardware.org/?probe=46271114d7) | Mar 01, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [1df5245912](https://linux-hardware.org/?probe=1df5245912) | Mar 01, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [bd438d0f08](https://linux-hardware.org/?probe=bd438d0f08) | Mar 01, 2022 |
| Dell          | Latitude E7240              | [4cf8d57b13](https://linux-hardware.org/?probe=4cf8d57b13) | Feb 28, 2022 |
| Apple         | MacBookPro11,2              | [eb57cef46a](https://linux-hardware.org/?probe=eb57cef46a) | Feb 28, 2022 |
| Dell          | Latitude E5400              | [ab5ce36275](https://linux-hardware.org/?probe=ab5ce36275) | Feb 27, 2022 |
| Dell          | XPS 15 9570                 | [b531665e82](https://linux-hardware.org/?probe=b531665e82) | Feb 27, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | [d3cc5d36be](https://linux-hardware.org/?probe=d3cc5d36be) | Feb 27, 2022 |
| Toshiba       | Satellite Pro A40-C         | [49766126e1](https://linux-hardware.org/?probe=49766126e1) | Feb 27, 2022 |
| HP            | Pavilion 15                 | [c68dd3c495](https://linux-hardware.org/?probe=c68dd3c495) | Feb 27, 2022 |
| Acer          | Aspire E1-472               | [3a735fdbc9](https://linux-hardware.org/?probe=3a735fdbc9) | Feb 27, 2022 |
| ASUSTek       | UL30A                       | [1fd1b8def7](https://linux-hardware.org/?probe=1fd1b8def7) | Feb 27, 2022 |
| ASUSTek       | K53Z                        | [0bd403b2c1](https://linux-hardware.org/?probe=0bd403b2c1) | Feb 25, 2022 |
| Dell          | Inspiron 7501               | [5da52fb35a](https://linux-hardware.org/?probe=5da52fb35a) | Feb 25, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IV... | [ec13490009](https://linux-hardware.org/?probe=ec13490009) | Feb 25, 2022 |
| Acer          | Aspire 5734Z                | [d23f71000a](https://linux-hardware.org/?probe=d23f71000a) | Feb 23, 2022 |
| Dell          | XPS 15 9500                 | [26fde0fb01](https://linux-hardware.org/?probe=26fde0fb01) | Feb 23, 2022 |
| Lenovo        | ThinkPad T450s 20BWS19E0... | [b1ea22a167](https://linux-hardware.org/?probe=b1ea22a167) | Feb 23, 2022 |
| MSI           | GT72 6QD                    | [7f4b5361a7](https://linux-hardware.org/?probe=7f4b5361a7) | Feb 23, 2022 |
| Dell          | Inspiron 5521               | [24bbdd3585](https://linux-hardware.org/?probe=24bbdd3585) | Feb 23, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | [1085285f79](https://linux-hardware.org/?probe=1085285f79) | Feb 22, 2022 |
| HP            | Stream Laptop 14-ax0XX      | [3285a9a5f6](https://linux-hardware.org/?probe=3285a9a5f6) | Feb 22, 2022 |
| HP            | EliteBook 8760w             | [cc9d99be2a](https://linux-hardware.org/?probe=cc9d99be2a) | Feb 22, 2022 |
| HP            | ENVY Laptop 13-ba1xxx       | [63fe1b47e9](https://linux-hardware.org/?probe=63fe1b47e9) | Feb 22, 2022 |
| Toshiba       | Satellite L300D             | [b930bd727d](https://linux-hardware.org/?probe=b930bd727d) | Feb 22, 2022 |
| Acer          | Aspire E5-511               | [e64ef61085](https://linux-hardware.org/?probe=e64ef61085) | Feb 21, 2022 |
| Apple         | MacBookPro8,1               | [d5968aba15](https://linux-hardware.org/?probe=d5968aba15) | Feb 21, 2022 |
| HP            | Laptop 14-dk0xxx            | [f0964465f1](https://linux-hardware.org/?probe=f0964465f1) | Feb 20, 2022 |
| MSI           | GF75 Thin 10UEK             | [07cbf077d9](https://linux-hardware.org/?probe=07cbf077d9) | Feb 19, 2022 |
| Toshiba       | Satellite S855D             | [2bbaf480f8](https://linux-hardware.org/?probe=2bbaf480f8) | Feb 19, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | [973e1c8d91](https://linux-hardware.org/?probe=973e1c8d91) | Feb 19, 2022 |
| HP            | EliteBook Folio 9480m       | [f53c1a8403](https://linux-hardware.org/?probe=f53c1a8403) | Feb 19, 2022 |
| HP            | Laptop 15-da2xxx            | [a504846e92](https://linux-hardware.org/?probe=a504846e92) | Feb 18, 2022 |
| Dell          | Inspiron 5521               | [1b52dd6cdf](https://linux-hardware.org/?probe=1b52dd6cdf) | Feb 18, 2022 |
| Dell          | XPS 15 9510                 | [04d70dfe98](https://linux-hardware.org/?probe=04d70dfe98) | Feb 18, 2022 |
| HP            | Notebook                    | [ab39875441](https://linux-hardware.org/?probe=ab39875441) | Feb 18, 2022 |
| Gateway       | EC14D                       | [8a943f6b57](https://linux-hardware.org/?probe=8a943f6b57) | Feb 18, 2022 |
| Lenovo        | ThinkPad T480 20L50067US    | [db1d64253e](https://linux-hardware.org/?probe=db1d64253e) | Feb 17, 2022 |
| Toshiba       | Satellite Z830              | [80ef3b4bda](https://linux-hardware.org/?probe=80ef3b4bda) | Feb 17, 2022 |
| System76      | Lemur Pro                   | [3a7527d1e3](https://linux-hardware.org/?probe=3a7527d1e3) | Feb 16, 2022 |
| Acer          | Aspire 7745                 | [59246d05e2](https://linux-hardware.org/?probe=59246d05e2) | Feb 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | [6b8d6986e4](https://linux-hardware.org/?probe=6b8d6986e4) | Feb 15, 2022 |
| Lenovo        | ThinkPad R61/R61i 8934A7... | [e60d5e52f2](https://linux-hardware.org/?probe=e60d5e52f2) | Feb 14, 2022 |
| Dell          | Latitude E6520              | [6238d2d306](https://linux-hardware.org/?probe=6238d2d306) | Feb 13, 2022 |
| ASUSTek       | G53SW                       | [5146b424cf](https://linux-hardware.org/?probe=5146b424cf) | Feb 13, 2022 |
| ASUSTek       | X541UAK                     | [402470c7c4](https://linux-hardware.org/?probe=402470c7c4) | Feb 12, 2022 |
| Apple         | MacBookAir7,2               | [91fa01f5a6](https://linux-hardware.org/?probe=91fa01f5a6) | Feb 12, 2022 |
| Apple         | MacBookAir7,2               | [dc1249f2a1](https://linux-hardware.org/?probe=dc1249f2a1) | Feb 12, 2022 |
| Dell          | Latitude E7240              | [3893c38bf7](https://linux-hardware.org/?probe=3893c38bf7) | Feb 11, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | [dda932e1ae](https://linux-hardware.org/?probe=dda932e1ae) | Feb 11, 2022 |
| HP            | EliteBook 2760p             | [a43d2b69e8](https://linux-hardware.org/?probe=a43d2b69e8) | Feb 11, 2022 |
| Dell          | XPS 15 9570                 | [dbfb51d331](https://linux-hardware.org/?probe=dbfb51d331) | Feb 10, 2022 |
| Lenovo        | ThinkPad T430 23427YU       | [82a3c63b3f](https://linux-hardware.org/?probe=82a3c63b3f) | Feb 10, 2022 |
| Acer          | Aspire 5735                 | [13c6c15c9e](https://linux-hardware.org/?probe=13c6c15c9e) | Feb 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [0c5853297a](https://linux-hardware.org/?probe=0c5853297a) | Feb 09, 2022 |
| Lenovo        | IdeaPad S340-14IWL 81N7     | [b7e0365760](https://linux-hardware.org/?probe=b7e0365760) | Feb 08, 2022 |
| Dell          | Latitude 7420               | [64178dcbb7](https://linux-hardware.org/?probe=64178dcbb7) | Feb 08, 2022 |
| Dell          | Precision M4700             | [192250957c](https://linux-hardware.org/?probe=192250957c) | Feb 08, 2022 |
| Dell          | Inspiron 7720               | [5b2eb74790](https://linux-hardware.org/?probe=5b2eb74790) | Feb 08, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [72ccc3b3a2](https://linux-hardware.org/?probe=72ccc3b3a2) | Feb 08, 2022 |
| Lenovo        | G570 20079                  | [61d85f383b](https://linux-hardware.org/?probe=61d85f383b) | Feb 08, 2022 |
| Dell          | Latitude E6420              | [3b262ed66a](https://linux-hardware.org/?probe=3b262ed66a) | Feb 08, 2022 |
| Acer          | Aspire F5-573T              | [0f3251e85b](https://linux-hardware.org/?probe=0f3251e85b) | Feb 08, 2022 |
| Dell          | XPS 13 9310                 | [740e7c0017](https://linux-hardware.org/?probe=740e7c0017) | Feb 07, 2022 |
| Dell          | Latitude E6540              | [aafec74a25](https://linux-hardware.org/?probe=aafec74a25) | Feb 07, 2022 |
| Dell          | Inspiron 1525               | [9291db4df4](https://linux-hardware.org/?probe=9291db4df4) | Feb 07, 2022 |
| Dell          | Latitude E5540              | [e895dcce0f](https://linux-hardware.org/?probe=e895dcce0f) | Feb 07, 2022 |
| Acer          | Okinawa                     | [e3251d31b8](https://linux-hardware.org/?probe=e3251d31b8) | Feb 07, 2022 |
| Apple         | MacBookAir6,2               | [2a1df5c52b](https://linux-hardware.org/?probe=2a1df5c52b) | Feb 06, 2022 |
| Acer          | Aspire A515-41G             | [0785fcc2af](https://linux-hardware.org/?probe=0785fcc2af) | Feb 06, 2022 |
| Dell          | Latitude E6410              | [63f2940a7b](https://linux-hardware.org/?probe=63f2940a7b) | Feb 05, 2022 |
| HP            | Pavilion Sleekbook 14       | [35ecfbbaf1](https://linux-hardware.org/?probe=35ecfbbaf1) | Feb 05, 2022 |
| HP            | EliteBook 2760p             | [7003664899](https://linux-hardware.org/?probe=7003664899) | Feb 05, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [404624d969](https://linux-hardware.org/?probe=404624d969) | Feb 05, 2022 |
| Dell          | Latitude E5450              | [84845ef09c](https://linux-hardware.org/?probe=84845ef09c) | Feb 04, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [3928781324](https://linux-hardware.org/?probe=3928781324) | Feb 04, 2022 |
| Dell          | Latitude E5450              | [fc7d07dba8](https://linux-hardware.org/?probe=fc7d07dba8) | Feb 04, 2022 |
| Panasonic     | CF-C2CHAZLDM                | [d684cb0ef2](https://linux-hardware.org/?probe=d684cb0ef2) | Feb 04, 2022 |
| Apple         | MacBookPro8,2               | [5b314a7764](https://linux-hardware.org/?probe=5b314a7764) | Feb 04, 2022 |
| Dell          | Latitude E6420              | [3c0a8a5e77](https://linux-hardware.org/?probe=3c0a8a5e77) | Feb 04, 2022 |
| Lenovo        | ThinkPad T460s 20FAS4QJ0... | [db476cb7bc](https://linux-hardware.org/?probe=db476cb7bc) | Feb 04, 2022 |
| Panasonic     | CF-31SBLJGDM                | [488b80a942](https://linux-hardware.org/?probe=488b80a942) | Feb 03, 2022 |
| Google        | Careena                     | [6d684ce669](https://linux-hardware.org/?probe=6d684ce669) | Feb 02, 2022 |
| Dell          | XPS 13 9305                 | [3db01f2b60](https://linux-hardware.org/?probe=3db01f2b60) | Feb 02, 2022 |
| Lenovo        | ThinkPad 11e 20DAS0VG00     | [ed24128e17](https://linux-hardware.org/?probe=ed24128e17) | Feb 02, 2022 |
| HUAWEI        | MACH-WX9                    | [4998bf6630](https://linux-hardware.org/?probe=4998bf6630) | Feb 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [387da722fe](https://linux-hardware.org/?probe=387da722fe) | Feb 02, 2022 |
| ASUSTek       | G73Jh                       | [8f48e553a3](https://linux-hardware.org/?probe=8f48e553a3) | Feb 02, 2022 |
| MSI           | GF75 Thin 10UEK             | [09274c49c4](https://linux-hardware.org/?probe=09274c49c4) | Feb 02, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [b16a5f611f](https://linux-hardware.org/?probe=b16a5f611f) | Feb 01, 2022 |
| Dell          | Precision 5530              | [5408c7e9ce](https://linux-hardware.org/?probe=5408c7e9ce) | Feb 01, 2022 |
| Dell          | Precision 5530              | [54fbbcf16a](https://linux-hardware.org/?probe=54fbbcf16a) | Jan 31, 2022 |
| Alienware     | 13 R2                       | [bc3b8ba7d5](https://linux-hardware.org/?probe=bc3b8ba7d5) | Jan 30, 2022 |
| Acer          | Aspire A315-21              | [98f458a763](https://linux-hardware.org/?probe=98f458a763) | Jan 30, 2022 |
| Alienware     | 13 R2                       | [112514da64](https://linux-hardware.org/?probe=112514da64) | Jan 29, 2022 |
| Acer          | Aspire 5742                 | [9c70e5839f](https://linux-hardware.org/?probe=9c70e5839f) | Jan 28, 2022 |
| Acer          | Aspire 5742                 | [26b0b3cf7b](https://linux-hardware.org/?probe=26b0b3cf7b) | Jan 28, 2022 |
| Dell          | Latitude D830               | [72c3dff322](https://linux-hardware.org/?probe=72c3dff322) | Jan 27, 2022 |
| HP            | Notebook                    | [2a363c2ced](https://linux-hardware.org/?probe=2a363c2ced) | Jan 27, 2022 |
| Dell          | XPS 17 9710                 | [d8e76e70e8](https://linux-hardware.org/?probe=d8e76e70e8) | Jan 26, 2022 |
| Acer          | Aspire A715-42G             | [b585a9d6bb](https://linux-hardware.org/?probe=b585a9d6bb) | Jan 26, 2022 |
| Sony          | SVE15127CDS                 | [b3908594f0](https://linux-hardware.org/?probe=b3908594f0) | Jan 26, 2022 |
| HP            | Laptop 15-ef2xxx            | [8394958e0e](https://linux-hardware.org/?probe=8394958e0e) | Jan 25, 2022 |
| Acer          | Okinawa                     | [e74688510a](https://linux-hardware.org/?probe=e74688510a) | Jan 24, 2022 |
| Framework     | Laptop                      | [99c660804f](https://linux-hardware.org/?probe=99c660804f) | Jan 24, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [8b4f45d131](https://linux-hardware.org/?probe=8b4f45d131) | Jan 24, 2022 |
| Acer          | Aspire 8920                 | [c2a3d58f23](https://linux-hardware.org/?probe=c2a3d58f23) | Jan 24, 2022 |
| Apple         | MacBookPro8,2               | [d1e0923b7a](https://linux-hardware.org/?probe=d1e0923b7a) | Jan 24, 2022 |
| Acer          | Aspire E5-521               | [8bd70502e5](https://linux-hardware.org/?probe=8bd70502e5) | Jan 24, 2022 |
| Framework     | Laptop                      | [47222fcb36](https://linux-hardware.org/?probe=47222fcb36) | Jan 23, 2022 |
| Acer          | Extensa 4630Z               | [40d8b3d26c](https://linux-hardware.org/?probe=40d8b3d26c) | Jan 23, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [92418aeb06](https://linux-hardware.org/?probe=92418aeb06) | Jan 22, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [cf76a7fc3f](https://linux-hardware.org/?probe=cf76a7fc3f) | Jan 22, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [b626f9fc62](https://linux-hardware.org/?probe=b626f9fc62) | Jan 21, 2022 |
| Sony          | VPCEB18FD                   | [5fbd1a31a6](https://linux-hardware.org/?probe=5fbd1a31a6) | Jan 21, 2022 |
| HP            | Laptop 15-bw0xx             | [6326f72eff](https://linux-hardware.org/?probe=6326f72eff) | Jan 21, 2022 |
| MSI           | GF75 Thin 10UEK             | [50ce7dd079](https://linux-hardware.org/?probe=50ce7dd079) | Jan 19, 2022 |
| ASUSTek       | X555QA                      | [3b78e2c833](https://linux-hardware.org/?probe=3b78e2c833) | Jan 19, 2022 |
| ASUSTek       | X555QA                      | [415ada273a](https://linux-hardware.org/?probe=415ada273a) | Jan 19, 2022 |
| Apple         | MacBookPro10,1              | [1aa2cd2e8f](https://linux-hardware.org/?probe=1aa2cd2e8f) | Jan 19, 2022 |
| Dell          | Inspiron 5593               | [d5f53520cb](https://linux-hardware.org/?probe=d5f53520cb) | Jan 18, 2022 |
| Dell          | Inspiron 5593               | [2abd85d6b2](https://linux-hardware.org/?probe=2abd85d6b2) | Jan 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [fcd259f1f2](https://linux-hardware.org/?probe=fcd259f1f2) | Jan 18, 2022 |
| MSI           | GP66 Leopard 11UH           | [bc394cac32](https://linux-hardware.org/?probe=bc394cac32) | Jan 17, 2022 |
| Lenovo        | IdeaPad 130S-11IGM 81KT     | [79fc7d53cf](https://linux-hardware.org/?probe=79fc7d53cf) | Jan 17, 2022 |
| HP            | G60                         | [0c45a490c6](https://linux-hardware.org/?probe=0c45a490c6) | Jan 17, 2022 |
| Lenovo        | ThinkPad T430 2347JC2       | [cac66153bc](https://linux-hardware.org/?probe=cac66153bc) | Jan 16, 2022 |
| Acer          | Aspire 5749Z                | [8441e54928](https://linux-hardware.org/?probe=8441e54928) | Jan 16, 2022 |
| Acer          | Aspire 5749Z                | [b375496bb6](https://linux-hardware.org/?probe=b375496bb6) | Jan 15, 2022 |
| HP            | ENVY m6                     | [60c739d5d3](https://linux-hardware.org/?probe=60c739d5d3) | Jan 15, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | [84b758e010](https://linux-hardware.org/?probe=84b758e010) | Jan 14, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [3927618884](https://linux-hardware.org/?probe=3927618884) | Jan 13, 2022 |
| Acer          | Aspire A515-54              | [87e7b56ed4](https://linux-hardware.org/?probe=87e7b56ed4) | Jan 13, 2022 |
| Lenovo        | ThinkPad T430u 3351CTO      | [41f9777fcf](https://linux-hardware.org/?probe=41f9777fcf) | Jan 13, 2022 |
| Toshiba       | Satellite L655              | [3735079aa3](https://linux-hardware.org/?probe=3735079aa3) | Jan 13, 2022 |
| Dell          | G5 5587                     | [f670d2c784](https://linux-hardware.org/?probe=f670d2c784) | Jan 13, 2022 |
| Lenovo        | Flex 2-15 20405             | [fef770b1ad](https://linux-hardware.org/?probe=fef770b1ad) | Jan 12, 2022 |
| Lenovo        | ThinkPad T420 4180AP4       | [03d9717183](https://linux-hardware.org/?probe=03d9717183) | Jan 11, 2022 |
| ASUSTek       | X510UAR                     | [fa5b04fccd](https://linux-hardware.org/?probe=fa5b04fccd) | Jan 11, 2022 |
| HP            | Compaq 6730b (KS180UT#AB... | [73043e1e90](https://linux-hardware.org/?probe=73043e1e90) | Jan 11, 2022 |
| HP            | Pavilion g6                 | [d90b661900](https://linux-hardware.org/?probe=d90b661900) | Jan 10, 2022 |
| ASUSTek       | 1215N                       | [faf4d2a7a7](https://linux-hardware.org/?probe=faf4d2a7a7) | Jan 10, 2022 |
| Unknown       | Unknown                     | [78e66c301e](https://linux-hardware.org/?probe=78e66c301e) | Jan 09, 2022 |
| Acer          | Aspire 5560                 | [5f4cda7891](https://linux-hardware.org/?probe=5f4cda7891) | Jan 09, 2022 |
| Toshiba       | Satellite L355              | [67f6de6410](https://linux-hardware.org/?probe=67f6de6410) | Jan 08, 2022 |
| Acer          | Aspire 5560                 | [9b8fbd16b6](https://linux-hardware.org/?probe=9b8fbd16b6) | Jan 08, 2022 |
| Lenovo        | IdeaPad Yoga 13 20175       | [ad8e8b92cb](https://linux-hardware.org/?probe=ad8e8b92cb) | Jan 08, 2022 |
| Acer          | Aspire A315-42              | [3a370523c5](https://linux-hardware.org/?probe=3a370523c5) | Jan 08, 2022 |
| Acer          | Aspire A315-42              | [d3dbc77cb6](https://linux-hardware.org/?probe=d3dbc77cb6) | Jan 08, 2022 |
| Dell          | Inspiron 11-3168            | [cd230f0c61](https://linux-hardware.org/?probe=cd230f0c61) | Jan 08, 2022 |
| Lenovo        | ThinkPad X390 20Q0CTO1WW    | [cf3fa03922](https://linux-hardware.org/?probe=cf3fa03922) | Jan 08, 2022 |
| Lenovo        | ThinkPad X390 20Q0CTO1WW    | [d62840031f](https://linux-hardware.org/?probe=d62840031f) | Jan 08, 2022 |
| Toshiba       | TECRA A50-C                 | [9ab17f5eae](https://linux-hardware.org/?probe=9ab17f5eae) | Jan 07, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [f85ea7cd3a](https://linux-hardware.org/?probe=f85ea7cd3a) | Jan 07, 2022 |
| Toshiba       | Satellite L355              | [267df555aa](https://linux-hardware.org/?probe=267df555aa) | Jan 07, 2022 |
| Dell          | Inspiron N5110              | [172b005a76](https://linux-hardware.org/?probe=172b005a76) | Jan 07, 2022 |
| Panasonic     | CF-195FYCALM                | [19ad0002e5](https://linux-hardware.org/?probe=19ad0002e5) | Jan 06, 2022 |
| Dell          | XPS 13 7390                 | [f1d9692c18](https://linux-hardware.org/?probe=f1d9692c18) | Jan 06, 2022 |
| Acer          | Aspire A315-42              | [b2d5bf7483](https://linux-hardware.org/?probe=b2d5bf7483) | Jan 06, 2022 |
| Acer          | Aspire E5-521               | [d10801b06e](https://linux-hardware.org/?probe=d10801b06e) | Jan 05, 2022 |
| Acer          | Aspire E5-521               | [014bf01c7d](https://linux-hardware.org/?probe=014bf01c7d) | Jan 05, 2022 |
| Dell          | Inspiron N5110              | [a0a13869ab](https://linux-hardware.org/?probe=a0a13869ab) | Jan 05, 2022 |
| Acer          | Aspire A315-21              | [9c47c4594d](https://linux-hardware.org/?probe=9c47c4594d) | Jan 05, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [56a85d54e4](https://linux-hardware.org/?probe=56a85d54e4) | Jan 04, 2022 |
| Dell          | Vostro 1520                 | [e010eae144](https://linux-hardware.org/?probe=e010eae144) | Jan 04, 2022 |
| Sony          | VPCF130FD                   | [f83b105795](https://linux-hardware.org/?probe=f83b105795) | Jan 04, 2022 |
| Dell          | Latitude E6540              | [665bf5dae7](https://linux-hardware.org/?probe=665bf5dae7) | Jan 04, 2022 |
| System76      | Lemur Pro                   | [6eda434d87](https://linux-hardware.org/?probe=6eda434d87) | Jan 03, 2022 |
| Apple         | MacBookPro8,1               | [eaf2e708d9](https://linux-hardware.org/?probe=eaf2e708d9) | Jan 03, 2022 |
| ATARI         | VCS 800 Classic             | [052eee7f7f](https://linux-hardware.org/?probe=052eee7f7f) | Jan 03, 2022 |
| ATARI         | VCS 800 Classic             | [b05fc0bc84](https://linux-hardware.org/?probe=b05fc0bc84) | Jan 03, 2022 |
| Dell          | XPS 15 7590                 | [b661a2cdf0](https://linux-hardware.org/?probe=b661a2cdf0) | Jan 03, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [7fa0610547](https://linux-hardware.org/?probe=7fa0610547) | Jan 02, 2022 |
| Gateway       | NE722                       | [a0d2bb6983](https://linux-hardware.org/?probe=a0d2bb6983) | Jan 01, 2022 |
| Dell          | Inspiron N5030              | [127df37eab](https://linux-hardware.org/?probe=127df37eab) | Jan 01, 2022 |
| Dell          | Inspiron N5030              | [fc6d58d758](https://linux-hardware.org/?probe=fc6d58d758) | Jan 01, 2022 |
| Acer          | Aspire A315-22              | [73ec029d3d](https://linux-hardware.org/?probe=73ec029d3d) | Dec 31, 2021 |
| Dell          | XPS 17 9710                 | [23110f625c](https://linux-hardware.org/?probe=23110f625c) | Dec 31, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [5d0bdd04cd](https://linux-hardware.org/?probe=5d0bdd04cd) | Dec 31, 2021 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | [4302dae812](https://linux-hardware.org/?probe=4302dae812) | Dec 31, 2021 |
| MSI           | GP75 Leopard 10SFK          | [f165698d96](https://linux-hardware.org/?probe=f165698d96) | Dec 29, 2021 |
| ASUSTek       | 1000H                       | [7b25815657](https://linux-hardware.org/?probe=7b25815657) | Dec 29, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [7f3028456e](https://linux-hardware.org/?probe=7f3028456e) | Dec 29, 2021 |
| HP            | Pavilion dv6                | [4c8838e815](https://linux-hardware.org/?probe=4c8838e815) | Dec 29, 2021 |
| Acer          | Aspire A315-22              | [69b22953b2](https://linux-hardware.org/?probe=69b22953b2) | Dec 29, 2021 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | [41b463b6c4](https://linux-hardware.org/?probe=41b463b6c4) | Dec 28, 2021 |
| Lenovo        | V330-15IKB 81AX             | [f68615959b](https://linux-hardware.org/?probe=f68615959b) | Dec 28, 2021 |
| Sony          | SVE15127CDS                 | [3d7ff31af5](https://linux-hardware.org/?probe=3d7ff31af5) | Dec 28, 2021 |
| Lenovo        | ThinkPad T550 20CKA00ECD    | [bea75ed7d5](https://linux-hardware.org/?probe=bea75ed7d5) | Dec 27, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [56c0a83ab8](https://linux-hardware.org/?probe=56c0a83ab8) | Dec 26, 2021 |
| Dell          | XPS 15 7590                 | [91780395d8](https://linux-hardware.org/?probe=91780395d8) | Dec 25, 2021 |
| MSI           | GF65 Thin 10UE              | [4457bc6367](https://linux-hardware.org/?probe=4457bc6367) | Dec 25, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [6fe369b6b7](https://linux-hardware.org/?probe=6fe369b6b7) | Dec 25, 2021 |
| ASUSTek       | X542UA                      | [c103fc5e33](https://linux-hardware.org/?probe=c103fc5e33) | Dec 24, 2021 |
| Dell          | Inspiron 15 5510            | [060d274be1](https://linux-hardware.org/?probe=060d274be1) | Dec 24, 2021 |
| Lenovo        | IdeaPad Yoga 13 20175       | [0c879745b1](https://linux-hardware.org/?probe=0c879745b1) | Dec 24, 2021 |
| Dell          | Inspiron N4010              | [bf8476146c](https://linux-hardware.org/?probe=bf8476146c) | Dec 24, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [7830e84ce4](https://linux-hardware.org/?probe=7830e84ce4) | Dec 23, 2021 |
| Lenovo        | ThinkPad E550 20DF0030US    | [384617e5a7](https://linux-hardware.org/?probe=384617e5a7) | Dec 22, 2021 |
| Lenovo        | ThinkPad E550 20DF0030US    | [8c9fc05c39](https://linux-hardware.org/?probe=8c9fc05c39) | Dec 22, 2021 |
| MSI           | GF75 Thin 10UEK             | [5d2da923d8](https://linux-hardware.org/?probe=5d2da923d8) | Dec 22, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA502IV... | [352c2b8493](https://linux-hardware.org/?probe=352c2b8493) | Dec 22, 2021 |
| Dell          | Inspiron 15 5510            | [e4d91f5636](https://linux-hardware.org/?probe=e4d91f5636) | Dec 21, 2021 |
| Dell          | Inspiron 15 5510            | [2018752b06](https://linux-hardware.org/?probe=2018752b06) | Dec 21, 2021 |
| Acer          | Aspire A515-54              | [39b1724ffa](https://linux-hardware.org/?probe=39b1724ffa) | Dec 20, 2021 |
| MSI           | GP63 Leopard 8RD            | [332c4bba00](https://linux-hardware.org/?probe=332c4bba00) | Dec 18, 2021 |
| System76      | Oryx Pro                    | [bb7fdaaa22](https://linux-hardware.org/?probe=bb7fdaaa22) | Dec 17, 2021 |
| Panasonic     | CF-31ACB7FPM                | [5bf09b5bb5](https://linux-hardware.org/?probe=5bf09b5bb5) | Dec 16, 2021 |
| Dell          | Latitude E6440              | [20ada84379](https://linux-hardware.org/?probe=20ada84379) | Dec 16, 2021 |
| System76      | Galago Pro                  | [e702cc7d76](https://linux-hardware.org/?probe=e702cc7d76) | Dec 16, 2021 |
| MSI           | GF75 Thin 10UEK             | [02bc8cb963](https://linux-hardware.org/?probe=02bc8cb963) | Dec 16, 2021 |
| Dell          | Latitude 5500               | [5b9479065e](https://linux-hardware.org/?probe=5b9479065e) | Dec 15, 2021 |
| Google        | Squawks                     | [e75aa07dad](https://linux-hardware.org/?probe=e75aa07dad) | Dec 15, 2021 |
| Lenovo        | ThinkPad T460 20FMS4U300    | [475a1f75a2](https://linux-hardware.org/?probe=475a1f75a2) | Dec 15, 2021 |
| HP            | EliteBook 8560p             | [6a1aefdd40](https://linux-hardware.org/?probe=6a1aefdd40) | Dec 14, 2021 |
| Sony          | SVS131290S                  | [9dffd4b7f9](https://linux-hardware.org/?probe=9dffd4b7f9) | Dec 14, 2021 |
| HP            | ProBook 6550b               | [ed38594f07](https://linux-hardware.org/?probe=ed38594f07) | Dec 13, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [d94711b81b](https://linux-hardware.org/?probe=d94711b81b) | Dec 13, 2021 |
| Google        | Squawks                     | [31cb595893](https://linux-hardware.org/?probe=31cb595893) | Dec 13, 2021 |
| ASUSTek       | X542UA                      | [920ca90cbe](https://linux-hardware.org/?probe=920ca90cbe) | Dec 13, 2021 |
| Acer          | Aspire A315-22              | [c7dec3c83d](https://linux-hardware.org/?probe=c7dec3c83d) | Dec 12, 2021 |
| Dell          | XPS 15 7590                 | [bf66a9a6b8](https://linux-hardware.org/?probe=bf66a9a6b8) | Dec 12, 2021 |
| Dell          | Precision M4600             | [f3f7be37a2](https://linux-hardware.org/?probe=f3f7be37a2) | Dec 12, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1H60... | [ffb1c97626](https://linux-hardware.org/?probe=ffb1c97626) | Dec 12, 2021 |
| ASUSTek       | X450LD                      | [b4f34fe662](https://linux-hardware.org/?probe=b4f34fe662) | Dec 11, 2021 |
| Acer          | Aspire A315-22              | [43938eb3c9](https://linux-hardware.org/?probe=43938eb3c9) | Dec 11, 2021 |
| HP            | Pavilion 15                 | [99645415a4](https://linux-hardware.org/?probe=99645415a4) | Dec 10, 2021 |
| ASUSTek       | X542UA                      | [e463e37acd](https://linux-hardware.org/?probe=e463e37acd) | Dec 10, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA502IV... | [4afc969d1d](https://linux-hardware.org/?probe=4afc969d1d) | Dec 10, 2021 |
| Toshiba       | Satellite C55t-C            | [0768ae5288](https://linux-hardware.org/?probe=0768ae5288) | Dec 10, 2021 |
| Acer          | Predator PH517-61           | [47706c797f](https://linux-hardware.org/?probe=47706c797f) | Dec 09, 2021 |
| Acer          | Aspire A315-22              | [4bc2eff89c](https://linux-hardware.org/?probe=4bc2eff89c) | Dec 08, 2021 |
| Dell          | Inspiron 1525               | [ae154367e4](https://linux-hardware.org/?probe=ae154367e4) | Dec 08, 2021 |
| Lenovo        | ThinkPad T400 741722U       | [2739940ec1](https://linux-hardware.org/?probe=2739940ec1) | Dec 08, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [ee8b533768](https://linux-hardware.org/?probe=ee8b533768) | Dec 07, 2021 |
| Dell          | Inspiron 5775               | [60c2ee09f1](https://linux-hardware.org/?probe=60c2ee09f1) | Dec 07, 2021 |
| Dell          | Inspiron 7773               | [2f7c3c0c0b](https://linux-hardware.org/?probe=2f7c3c0c0b) | Dec 07, 2021 |
| Lenovo        | ThinkPad T400 741722U       | [2933ad8c69](https://linux-hardware.org/?probe=2933ad8c69) | Dec 07, 2021 |
| HP            | Laptop 14-fq0xxx            | [ff96678e1c](https://linux-hardware.org/?probe=ff96678e1c) | Dec 07, 2021 |
| Acer          | Aspire A315-21              | [2425031333](https://linux-hardware.org/?probe=2425031333) | Dec 07, 2021 |
| Dell          | Inspiron 1525               | [759aef7156](https://linux-hardware.org/?probe=759aef7156) | Dec 06, 2021 |
| Unknown       | Unknown                     | [e876d7e83d](https://linux-hardware.org/?probe=e876d7e83d) | Dec 06, 2021 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [3c678945c5](https://linux-hardware.org/?probe=3c678945c5) | Dec 06, 2021 |
| HP            | Laptop 14-fq0xxx            | [52cc15a168](https://linux-hardware.org/?probe=52cc15a168) | Dec 06, 2021 |
| Lenovo        | ThinkPad W520 42763JF       | [50d1714228](https://linux-hardware.org/?probe=50d1714228) | Dec 05, 2021 |
| Dell          | Latitude E6410              | [07ca5fc75a](https://linux-hardware.org/?probe=07ca5fc75a) | Dec 05, 2021 |
| ASUSTek       | X553MA                      | [958551b7eb](https://linux-hardware.org/?probe=958551b7eb) | Dec 05, 2021 |
| Acer          | Aspire A315-21              | [b6e4b7efdc](https://linux-hardware.org/?probe=b6e4b7efdc) | Dec 04, 2021 |
| Acer          | Aspire 5810T                | [db8b8d11fa](https://linux-hardware.org/?probe=db8b8d11fa) | Dec 04, 2021 |
| ASUSTek       | X553MA                      | [78414b8bc4](https://linux-hardware.org/?probe=78414b8bc4) | Dec 04, 2021 |
| Lenovo        | ThinkPad W520 42763JF       | [23d42021b2](https://linux-hardware.org/?probe=23d42021b2) | Dec 04, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [b49088935d](https://linux-hardware.org/?probe=b49088935d) | Dec 04, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [7cdf0f8f44](https://linux-hardware.org/?probe=7cdf0f8f44) | Dec 04, 2021 |
| Lenovo        | ThinkPad T500 2089R97       | [6a2cd8a43a](https://linux-hardware.org/?probe=6a2cd8a43a) | Dec 03, 2021 |
| Acer          | Nitro AN515-55              | [25bfc653d8](https://linux-hardware.org/?probe=25bfc653d8) | Dec 03, 2021 |
| ASUSTek       | X555BA                      | [30f34299fd](https://linux-hardware.org/?probe=30f34299fd) | Dec 03, 2021 |
| Lenovo        | ThinkPad T500 2089R97       | [690a59fee2](https://linux-hardware.org/?probe=690a59fee2) | Dec 03, 2021 |
| HP            | EliteBook 8560p             | [54f7f8dbfa](https://linux-hardware.org/?probe=54f7f8dbfa) | Dec 03, 2021 |
| Dell          | Latitude E5570              | [d7beab52f4](https://linux-hardware.org/?probe=d7beab52f4) | Dec 02, 2021 |
| Toshiba       | Satellite A305              | [6ab5487eb7](https://linux-hardware.org/?probe=6ab5487eb7) | Dec 01, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [8cebf41624](https://linux-hardware.org/?probe=8cebf41624) | Dec 01, 2021 |
| Acer          | Nitro AN515-55              | [b070b0e028](https://linux-hardware.org/?probe=b070b0e028) | Nov 30, 2021 |
| Acer          | V5-171                      | [63a4cced51](https://linux-hardware.org/?probe=63a4cced51) | Nov 29, 2021 |
| Lenovo        | Unknown                     | [52bd32224a](https://linux-hardware.org/?probe=52bd32224a) | Nov 29, 2021 |
| Acer          | Aspire A515-56              | [b0ed9bece9](https://linux-hardware.org/?probe=b0ed9bece9) | Nov 28, 2021 |
| Dell          | XPS 15 7590                 | [6b4fb72d69](https://linux-hardware.org/?probe=6b4fb72d69) | Nov 28, 2021 |
| Dell          | Latitude E6430              | [a7435eb4c7](https://linux-hardware.org/?probe=a7435eb4c7) | Nov 28, 2021 |
| Lenovo        | ThinkPad T470s 20HF003QU... | [891d5afaba](https://linux-hardware.org/?probe=891d5afaba) | Nov 28, 2021 |
| Lenovo        | ThinkPad E520 1143AD5       | [c76e2c7b06](https://linux-hardware.org/?probe=c76e2c7b06) | Nov 27, 2021 |
| Dell          | Latitude E6510              | [9f89e081fa](https://linux-hardware.org/?probe=9f89e081fa) | Nov 26, 2021 |
| ASUSTek       | K54C                        | [2604de426e](https://linux-hardware.org/?probe=2604de426e) | Nov 26, 2021 |
| Dell          | Inspiron 15-3573            | [04dc1956ff](https://linux-hardware.org/?probe=04dc1956ff) | Nov 26, 2021 |
| Toshiba       | Satellite L500              | [24645f6ab5](https://linux-hardware.org/?probe=24645f6ab5) | Nov 26, 2021 |
| MSI           | MS-1034                     | [bbf051d81a](https://linux-hardware.org/?probe=bbf051d81a) | Nov 26, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [8ddedf25c1](https://linux-hardware.org/?probe=8ddedf25c1) | Nov 26, 2021 |
| Lenovo        | ThinkPad W700 2752RZ2       | [66ea0a02cb](https://linux-hardware.org/?probe=66ea0a02cb) | Nov 25, 2021 |
| Dell          | Inspiron 1545               | [d8d0d4f7e5](https://linux-hardware.org/?probe=d8d0d4f7e5) | Nov 25, 2021 |
| Acer          | Aspire 7551                 | [a224e9c96b](https://linux-hardware.org/?probe=a224e9c96b) | Nov 25, 2021 |
| Dell          | Latitude E6430              | [f18bb8ac48](https://linux-hardware.org/?probe=f18bb8ac48) | Nov 24, 2021 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [89592b060d](https://linux-hardware.org/?probe=89592b060d) | Nov 24, 2021 |
| Dell          | Inspiron 1545               | [a05285a835](https://linux-hardware.org/?probe=a05285a835) | Nov 23, 2021 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [649434f9b8](https://linux-hardware.org/?probe=649434f9b8) | Nov 23, 2021 |
| Dell          | Latitude E6430              | [ce21d5f8d7](https://linux-hardware.org/?probe=ce21d5f8d7) | Nov 23, 2021 |
| Apple         | MacBookPro11,5              | [9a09876c14](https://linux-hardware.org/?probe=9a09876c14) | Nov 22, 2021 |
| Toshiba       | Satellite L500              | [30bfdcb5ff](https://linux-hardware.org/?probe=30bfdcb5ff) | Nov 22, 2021 |
| HP            | ProBook 6470b               | [412bdcf6b1](https://linux-hardware.org/?probe=412bdcf6b1) | Nov 22, 2021 |
| Apple         | MacBook4,1                  | [025147c895](https://linux-hardware.org/?probe=025147c895) | Nov 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [39d84bdde8](https://linux-hardware.org/?probe=39d84bdde8) | Nov 22, 2021 |
| Dell          | Latitude E6440              | [babff23db6](https://linux-hardware.org/?probe=babff23db6) | Nov 21, 2021 |
| MSI           | GF75 Thin 10UEK             | [afc01e4eac](https://linux-hardware.org/?probe=afc01e4eac) | Nov 21, 2021 |
| ASUSTek       | K53E                        | [376e053c8c](https://linux-hardware.org/?probe=376e053c8c) | Nov 20, 2021 |
| Dell          | Inspiron 7577               | [06399f0deb](https://linux-hardware.org/?probe=06399f0deb) | Nov 20, 2021 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [a3d3e0eecd](https://linux-hardware.org/?probe=a3d3e0eecd) | Nov 20, 2021 |
| Sony          | VPCF130FD                   | [e4468538f5](https://linux-hardware.org/?probe=e4468538f5) | Nov 19, 2021 |
| Dell          | Latitude 5480               | [0d20c308b5](https://linux-hardware.org/?probe=0d20c308b5) | Nov 18, 2021 |
| HP            | ProBook 6470b               | [2f11f08d49](https://linux-hardware.org/?probe=2f11f08d49) | Nov 18, 2021 |
| HP            | ProBook 6470b               | [dd0607282d](https://linux-hardware.org/?probe=dd0607282d) | Nov 18, 2021 |
| HP            | ProBook 6470b               | [f50d51ecfc](https://linux-hardware.org/?probe=f50d51ecfc) | Nov 18, 2021 |
| Acer          | Aspire 7740                 | [5d1edffce5](https://linux-hardware.org/?probe=5d1edffce5) | Nov 17, 2021 |
| MSI           | GS60 6QE                    | [69d43f9c20](https://linux-hardware.org/?probe=69d43f9c20) | Nov 17, 2021 |
| Acer          | Swift SF314-56              | [facd9bfb3a](https://linux-hardware.org/?probe=facd9bfb3a) | Nov 17, 2021 |
| Dell          | Inspiron 1545               | [f5a7f54888](https://linux-hardware.org/?probe=f5a7f54888) | Nov 16, 2021 |
| Acer          | Swift SF314-52              | [58ba001f88](https://linux-hardware.org/?probe=58ba001f88) | Nov 14, 2021 |
| Samsung       | 900X3C/900X3D/900X4C/900... | [76b69deb69](https://linux-hardware.org/?probe=76b69deb69) | Nov 14, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [791ae651bb](https://linux-hardware.org/?probe=791ae651bb) | Nov 14, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [b105aaabf5](https://linux-hardware.org/?probe=b105aaabf5) | Nov 14, 2021 |
| Dell          | Vostro 3700                 | [fec6ecb249](https://linux-hardware.org/?probe=fec6ecb249) | Nov 14, 2021 |
| HP            | Stream Laptop 14-ax0XX      | [3bd51f200e](https://linux-hardware.org/?probe=3bd51f200e) | Nov 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [78651b05bb](https://linux-hardware.org/?probe=78651b05bb) | Nov 13, 2021 |
| Dell          | G15 5510                    | [178497a15b](https://linux-hardware.org/?probe=178497a15b) | Nov 12, 2021 |
| Dell          | Precision M4700             | [8d8a2dcc96](https://linux-hardware.org/?probe=8d8a2dcc96) | Nov 12, 2021 |
| Gigabyte      | Unknown                     | [a5f960e4ad](https://linux-hardware.org/?probe=a5f960e4ad) | Nov 12, 2021 |
| Apple         | MacBookPro7,1               | [62af0283db](https://linux-hardware.org/?probe=62af0283db) | Nov 12, 2021 |
| Apple         | MacBookPro7,1               | [a4179da526](https://linux-hardware.org/?probe=a4179da526) | Nov 12, 2021 |
| Apple         | MacBookPro11,5              | [401da402d8](https://linux-hardware.org/?probe=401da402d8) | Nov 12, 2021 |
| Apple         | MacBookPro11,5              | [7daf6ea0a5](https://linux-hardware.org/?probe=7daf6ea0a5) | Nov 12, 2021 |
| Lenovo        | IdeaPad 300-17ISK 80QH      | [c948868090](https://linux-hardware.org/?probe=c948868090) | Nov 11, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [ac9d7f968f](https://linux-hardware.org/?probe=ac9d7f968f) | Nov 10, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [a008880313](https://linux-hardware.org/?probe=a008880313) | Nov 10, 2021 |
| System76      | Galago Pro                  | [0aff467123](https://linux-hardware.org/?probe=0aff467123) | Nov 10, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [498eb8af8b](https://linux-hardware.org/?probe=498eb8af8b) | Nov 09, 2021 |
| Sony          | VPCCB25FX                   | [c42c92c898](https://linux-hardware.org/?probe=c42c92c898) | Nov 09, 2021 |
| Dell          | Latitude E6420              | [0cd7346e6d](https://linux-hardware.org/?probe=0cd7346e6d) | Nov 09, 2021 |
| Dell          | Precision 7510              | [4729694e52](https://linux-hardware.org/?probe=4729694e52) | Nov 08, 2021 |
| Dell          | Inspiron 1545               | [4816b0f951](https://linux-hardware.org/?probe=4816b0f951) | Nov 08, 2021 |
| ASUSTek       | ROG Strix G531GT_GL531GT    | [685c3c0f3f](https://linux-hardware.org/?probe=685c3c0f3f) | Nov 08, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [81237c05f7](https://linux-hardware.org/?probe=81237c05f7) | Nov 08, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [d7a0b05df7](https://linux-hardware.org/?probe=d7a0b05df7) | Nov 07, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [cd1647c038](https://linux-hardware.org/?probe=cd1647c038) | Nov 07, 2021 |
| Dell          | XPS 15 7590                 | [53cfd83c43](https://linux-hardware.org/?probe=53cfd83c43) | Nov 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [b4c93f107b](https://linux-hardware.org/?probe=b4c93f107b) | Nov 07, 2021 |
| Lenovo        | IdeaPad 300-17ISK 80QH      | [520a472266](https://linux-hardware.org/?probe=520a472266) | Nov 07, 2021 |
| Dell          | G3 3500                     | [acc14d7efc](https://linux-hardware.org/?probe=acc14d7efc) | Nov 07, 2021 |
| Dell          | Precision M4600             | [acd5115099](https://linux-hardware.org/?probe=acd5115099) | Nov 06, 2021 |
| MSI           | GL63 8RC                    | [068ed7518b](https://linux-hardware.org/?probe=068ed7518b) | Nov 06, 2021 |
| Dell          | G3 3500                     | [ea3cdd3cc4](https://linux-hardware.org/?probe=ea3cdd3cc4) | Nov 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [617d2f5444](https://linux-hardware.org/?probe=617d2f5444) | Nov 06, 2021 |
| ASUSTek       | ROG Strix G512LI_G512LI     | [e43a236a2c](https://linux-hardware.org/?probe=e43a236a2c) | Nov 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [0c1490178d](https://linux-hardware.org/?probe=0c1490178d) | Nov 06, 2021 |
| Acer          | Aspire 5741G                | [95dba04fb0](https://linux-hardware.org/?probe=95dba04fb0) | Nov 05, 2021 |
| Acer          | Nitro AN715-52              | [d7fe8595a3](https://linux-hardware.org/?probe=d7fe8595a3) | Nov 05, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [9d85113feb](https://linux-hardware.org/?probe=9d85113feb) | Nov 05, 2021 |
| Lenovo        | ThinkPad W530 24384CU       | [d18d3495e0](https://linux-hardware.org/?probe=d18d3495e0) | Nov 05, 2021 |
| Lenovo        | ThinkPad T410 25222AU       | [b1abc5b653](https://linux-hardware.org/?probe=b1abc5b653) | Nov 05, 2021 |
| Acer          | Nitro AN515-54              | [8859c97474](https://linux-hardware.org/?probe=8859c97474) | Nov 05, 2021 |
| Google        | Peppy                       | [70e66a372f](https://linux-hardware.org/?probe=70e66a372f) | Nov 04, 2021 |
| Lenovo        | ThinkPad X230 23252UU       | [8e8f78281b](https://linux-hardware.org/?probe=8e8f78281b) | Nov 04, 2021 |
| Dell          | XPS 15 7590                 | [d854ecb9f9](https://linux-hardware.org/?probe=d854ecb9f9) | Nov 04, 2021 |
| Dell          | Precision M4600             | [155f9ec4f4](https://linux-hardware.org/?probe=155f9ec4f4) | Nov 04, 2021 |
| HP            | Pavilion dv6                | [0f40b6f961](https://linux-hardware.org/?probe=0f40b6f961) | Nov 04, 2021 |
| HP            | Pavilion dv6                | [91497e1d93](https://linux-hardware.org/?probe=91497e1d93) | Nov 04, 2021 |
| Apple         | MacBookPro9,2               | [34b9284bc8](https://linux-hardware.org/?probe=34b9284bc8) | Nov 03, 2021 |
| Lenovo        | ThinkPad X395 20NL0005US    | [b65f4d5ba3](https://linux-hardware.org/?probe=b65f4d5ba3) | Nov 03, 2021 |
| GPD           | P2 MAX                      | [9adb3fd2eb](https://linux-hardware.org/?probe=9adb3fd2eb) | Nov 02, 2021 |
| HP            | EliteBook 840 G3            | [6376d7464b](https://linux-hardware.org/?probe=6376d7464b) | Nov 02, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [de36837a42](https://linux-hardware.org/?probe=de36837a42) | Nov 02, 2021 |
| ASUSTek       | K50IJ                       | [905e53768d](https://linux-hardware.org/?probe=905e53768d) | Nov 02, 2021 |
| Toshiba       | Satellite A305              | [701b48d3f0](https://linux-hardware.org/?probe=701b48d3f0) | Nov 02, 2021 |
| ASUSTek       | GL553VE                     | [22b5b29b32](https://linux-hardware.org/?probe=22b5b29b32) | Nov 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [c1965ee087](https://linux-hardware.org/?probe=c1965ee087) | Nov 01, 2021 |
| MSI           | GL63 8RC                    | [ad6c3506c1](https://linux-hardware.org/?probe=ad6c3506c1) | Nov 01, 2021 |
| ASUSTek       | ROG Strix G512LI_G512LI     | [32f01ccaab](https://linux-hardware.org/?probe=32f01ccaab) | Oct 31, 2021 |
| Toshiba       | QOSMIO F60                  | [c319ec4a5f](https://linux-hardware.org/?probe=c319ec4a5f) | Oct 31, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [22728e37fe](https://linux-hardware.org/?probe=22728e37fe) | Oct 31, 2021 |
| Apple         | MacBookPro11,1              | [0c24caf245](https://linux-hardware.org/?probe=0c24caf245) | Oct 31, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [68a5bdc18a](https://linux-hardware.org/?probe=68a5bdc18a) | Oct 31, 2021 |
| Dell          | Precision M4600             | [f442df91a1](https://linux-hardware.org/?probe=f442df91a1) | Oct 31, 2021 |
| Unknown       | MT8117                      | [b579146661](https://linux-hardware.org/?probe=b579146661) | Oct 31, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [0f6d7bcf66](https://linux-hardware.org/?probe=0f6d7bcf66) | Oct 31, 2021 |
| MSI           | GT75VR 7RF                  | [edd545a455](https://linux-hardware.org/?probe=edd545a455) | Oct 30, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [1310b8abf4](https://linux-hardware.org/?probe=1310b8abf4) | Oct 30, 2021 |
| Dell          | Latitude 7370               | [6bf3c3796e](https://linux-hardware.org/?probe=6bf3c3796e) | Oct 30, 2021 |
| MSI           | GE62 7RD                    | [95616813e6](https://linux-hardware.org/?probe=95616813e6) | Oct 29, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [48434e75fb](https://linux-hardware.org/?probe=48434e75fb) | Oct 28, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [13addb7994](https://linux-hardware.org/?probe=13addb7994) | Oct 28, 2021 |
| HP            | ProBook 440 G5              | [3790956b6e](https://linux-hardware.org/?probe=3790956b6e) | Oct 28, 2021 |
| HP            | ProBook 440 G5              | [e346ffdcd9](https://linux-hardware.org/?probe=e346ffdcd9) | Oct 28, 2021 |
| MSI           | MS-1034                     | [f1770353a3](https://linux-hardware.org/?probe=f1770353a3) | Oct 28, 2021 |
| Acer          | Aspire one                  | [d64d1f97c4](https://linux-hardware.org/?probe=d64d1f97c4) | Oct 27, 2021 |
| HP            | 2000                        | [65ec913842](https://linux-hardware.org/?probe=65ec913842) | Oct 27, 2021 |
| Apple         | MacBook2,1                  | [0346bc764a](https://linux-hardware.org/?probe=0346bc764a) | Oct 27, 2021 |
| Acer          | Aspire A315-21              | [e179a0974d](https://linux-hardware.org/?probe=e179a0974d) | Oct 27, 2021 |
| ASUSTek       | ROG Strix G712LV_G712LV     | [2c2443341f](https://linux-hardware.org/?probe=2c2443341f) | Oct 27, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [51b5e6cb3f](https://linux-hardware.org/?probe=51b5e6cb3f) | Oct 26, 2021 |
| Dell          | Latitude E6540              | [298ab39418](https://linux-hardware.org/?probe=298ab39418) | Oct 26, 2021 |
| Fujitsu       | LIFEBOOK AH530              | [ed4e9d1a03](https://linux-hardware.org/?probe=ed4e9d1a03) | Oct 26, 2021 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [16306ffb37](https://linux-hardware.org/?probe=16306ffb37) | Oct 25, 2021 |
| Lenovo        | ThinkPad X230 2320HMU       | [2139d7269b](https://linux-hardware.org/?probe=2139d7269b) | Oct 25, 2021 |
| HP            | Pavilion g6                 | [2c2d7620f9](https://linux-hardware.org/?probe=2c2d7620f9) | Oct 25, 2021 |
| HP            | ProBook 6470b               | [7aa667ba1a](https://linux-hardware.org/?probe=7aa667ba1a) | Oct 25, 2021 |
| Acer          | Aspire E5-571               | [11ebf2008b](https://linux-hardware.org/?probe=11ebf2008b) | Oct 24, 2021 |
| HP            | ProBook 440 G5              | [2bfda565c4](https://linux-hardware.org/?probe=2bfda565c4) | Oct 24, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [0e7d8c6503](https://linux-hardware.org/?probe=0e7d8c6503) | Oct 23, 2021 |
| Acer          | Aspire 5560                 | [39fd26f895](https://linux-hardware.org/?probe=39fd26f895) | Oct 22, 2021 |
| HP            | ProBook 440 G5              | [2bc543a497](https://linux-hardware.org/?probe=2bc543a497) | Oct 22, 2021 |
| Apple         | MacBookPro9,2               | [733cccb53c](https://linux-hardware.org/?probe=733cccb53c) | Oct 22, 2021 |
| LG Electro... | X120-L.C7L1A9               | [42b7007a7e](https://linux-hardware.org/?probe=42b7007a7e) | Oct 21, 2021 |
| ASUSTek       | PRIME X570-PRO              | [e02455114e](https://linux-hardware.org/?probe=e02455114e) | Oct 21, 2021 |
| Lenovo        | ThinkPad X130e 0629A12      | [6bb2a39e4f](https://linux-hardware.org/?probe=6bb2a39e4f) | Oct 21, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [c89111fc95](https://linux-hardware.org/?probe=c89111fc95) | Oct 21, 2021 |
| HP            | Dratini                     | [fe5d417b15](https://linux-hardware.org/?probe=fe5d417b15) | Oct 20, 2021 |
| Dell          | Vostro 3558                 | [730641b494](https://linux-hardware.org/?probe=730641b494) | Oct 20, 2021 |
| Apple         | MacBookPro16,2              | [2fdc29f9cb](https://linux-hardware.org/?probe=2fdc29f9cb) | Oct 20, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [6214c9eb86](https://linux-hardware.org/?probe=6214c9eb86) | Oct 20, 2021 |
| Gateway       | NV55S                       | [0781065494](https://linux-hardware.org/?probe=0781065494) | Oct 20, 2021 |
| Gateway       | NV55S                       | [562bd81383](https://linux-hardware.org/?probe=562bd81383) | Oct 20, 2021 |
| Fujitsu       | LIFEBOOK AH530              | [15ce74dcd6](https://linux-hardware.org/?probe=15ce74dcd6) | Oct 17, 2021 |
| Fujitsu       | LIFEBOOK AH530              | [97c3495c65](https://linux-hardware.org/?probe=97c3495c65) | Oct 17, 2021 |
| Dell          | Latitude E6420              | [cbbc802431](https://linux-hardware.org/?probe=cbbc802431) | Oct 17, 2021 |
| HUAWEI        | WRT-WX9                     | [d9cd722532](https://linux-hardware.org/?probe=d9cd722532) | Oct 17, 2021 |
| Lenovo        | ThinkPad X130e 0629A12      | [def46150b4](https://linux-hardware.org/?probe=def46150b4) | Oct 16, 2021 |
| HP            | EliteBook 8570w             | [492907a363](https://linux-hardware.org/?probe=492907a363) | Oct 16, 2021 |
| Dell          | System XPS 15Z              | [f004e8e996](https://linux-hardware.org/?probe=f004e8e996) | Oct 16, 2021 |
| Acer          | Aspire V3-575               | [65061ec6b1](https://linux-hardware.org/?probe=65061ec6b1) | Oct 15, 2021 |
| HP            | EliteBook Folio 9470m       | [1c49ebee5f](https://linux-hardware.org/?probe=1c49ebee5f) | Oct 14, 2021 |
| Toshiba       | Satellite C55D-A            | [087fc97d07](https://linux-hardware.org/?probe=087fc97d07) | Oct 13, 2021 |
| ASUSTek       | X555DA                      | [a08da25590](https://linux-hardware.org/?probe=a08da25590) | Oct 13, 2021 |
| ASUSTek       | X541NA                      | [64bc2367ef](https://linux-hardware.org/?probe=64bc2367ef) | Oct 13, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [6bd6fd9002](https://linux-hardware.org/?probe=6bd6fd9002) | Oct 12, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [1f91e82c9f](https://linux-hardware.org/?probe=1f91e82c9f) | Oct 12, 2021 |
| MSI           | GF75 Thin 10UEK             | [d7ca508313](https://linux-hardware.org/?probe=d7ca508313) | Oct 12, 2021 |
| ASUSTek       | ROG Zephyrus GX550LWS_GX... | [1952252a77](https://linux-hardware.org/?probe=1952252a77) | Oct 12, 2021 |
| HP            | ProBook 650 G4              | [ea1c62ead1](https://linux-hardware.org/?probe=ea1c62ead1) | Oct 12, 2021 |
| HP            | EliteBook 840 G1            | [9bb8ba744e](https://linux-hardware.org/?probe=9bb8ba744e) | Oct 12, 2021 |
| HP            | 2000                        | [9f27a8ee7c](https://linux-hardware.org/?probe=9f27a8ee7c) | Oct 11, 2021 |
| HP            | 2000                        | [30a94a8c46](https://linux-hardware.org/?probe=30a94a8c46) | Oct 11, 2021 |
| Dell          | Inspiron 13-7378            | [43f15f79df](https://linux-hardware.org/?probe=43f15f79df) | Oct 11, 2021 |
| Dell          | Latitude E6520              | [1e3b469a11](https://linux-hardware.org/?probe=1e3b469a11) | Oct 10, 2021 |
| Dell          | Latitude E4300              | [c486155f48](https://linux-hardware.org/?probe=c486155f48) | Oct 10, 2021 |
| Dell          | Latitude E4300              | [52e0d626fa](https://linux-hardware.org/?probe=52e0d626fa) | Oct 10, 2021 |
| Alienware     | M11x R2                     | [3489d7096d](https://linux-hardware.org/?probe=3489d7096d) | Oct 10, 2021 |
| Lenovo        | ThinkPad T420s 417152U      | [4f47dc5c55](https://linux-hardware.org/?probe=4f47dc5c55) | Oct 09, 2021 |
| Samsung       | 700Z3C/700Z5C               | [007ba2bac1](https://linux-hardware.org/?probe=007ba2bac1) | Oct 09, 2021 |
| Lenovo        | IdeaPad Y510P 20217         | [4e1f134c9a](https://linux-hardware.org/?probe=4e1f134c9a) | Oct 09, 2021 |
| HP            | ENVY Laptop 13-ba1xxx       | [ab4e6ed1fb](https://linux-hardware.org/?probe=ab4e6ed1fb) | Oct 09, 2021 |
| Dell          | Inspiron 15-3567            | [07648f2b81](https://linux-hardware.org/?probe=07648f2b81) | Oct 08, 2021 |
| Dell          | Inspiron 5505               | [d136f5d8f7](https://linux-hardware.org/?probe=d136f5d8f7) | Oct 08, 2021 |
| Samsung       | 550P5C/550P7C               | [8f23eabf26](https://linux-hardware.org/?probe=8f23eabf26) | Oct 08, 2021 |
| Acer          | Aspire E5-573T              | [749a8c4ccc](https://linux-hardware.org/?probe=749a8c4ccc) | Oct 07, 2021 |
| HP            | Stream Laptop 14-ax0XX      | [8594f59481](https://linux-hardware.org/?probe=8594f59481) | Oct 06, 2021 |
| MSI           | GF75 Thin 10UEK             | [9fb9daffbc](https://linux-hardware.org/?probe=9fb9daffbc) | Oct 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [42bb3aa5db](https://linux-hardware.org/?probe=42bb3aa5db) | Oct 06, 2021 |
| ASUSTek       | X550EA                      | [bbed87466a](https://linux-hardware.org/?probe=bbed87466a) | Oct 05, 2021 |
| Dell          | Latitude E6430              | [3d605c2c36](https://linux-hardware.org/?probe=3d605c2c36) | Oct 05, 2021 |
| Dell          | Inspiron 5775               | [1f37c7ca65](https://linux-hardware.org/?probe=1f37c7ca65) | Oct 05, 2021 |
| Dell          | Inspiron 5775               | [c42e665e24](https://linux-hardware.org/?probe=c42e665e24) | Oct 05, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Canada/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Ubuntu 20.04      | 347       | 15.83%  |
| Ubuntu 18.04      | 198       | 9.03%   |
| KDE neon 20.04    | 50        | 2.28%   |
| OpenMandriva 4.2  | 48        | 2.19%   |
| Arch              | 48        | 2.19%   |
| Zorin 15          | 43        | 1.96%   |
| Manjaro           | 43        | 1.96%   |
| Xubuntu 20.04     | 42        | 1.92%   |
| Linux Mint 20.3   | 41        | 1.87%   |
| Ubuntu 19.10      | 39        | 1.78%   |
| OpenMandriva 4.3  | 39        | 1.78%   |
| Pop!_OS 21.04     | 38        | 1.73%   |
| Zorin 16          | 37        | 1.69%   |
| Ubuntu 22.04      | 37        | 1.69%   |
| Linux Mint 19.3   | 37        | 1.69%   |
| Pop!_OS 20.04     | 36        | 1.64%   |
| Fedora 35         | 35        | 1.6%    |
| Debian 11         | 34        | 1.55%   |
| Ubuntu 21.10      | 33        | 1.51%   |
| Linux Mint 20.1   | 31        | 1.41%   |
| Ubuntu 20.10      | 30        | 1.37%   |
| Pop!_OS 20.10     | 29        | 1.32%   |
| Linux Mint 20.2   | 28        | 1.28%   |
| ArcoLinux Rolling | 28        | 1.28%   |
| Ubuntu 19.04      | 27        | 1.23%   |
| Pop!_OS 22.04     | 26        | 1.19%   |
| Linux Mint 20     | 24        | 1.09%   |
| Fedora 32         | 24        | 1.09%   |
| Pop!_OS 21.10     | 23        | 1.05%   |
| Arch Rolling      | 23        | 1.05%   |
| Ubuntu 21.04      | 22        | 1%      |
| Fedora 33         | 22        | 1%      |
| Fedora 31         | 20        | 0.91%   |
| Fedora 36         | 19        | 0.87%   |
| Fedora 34         | 19        | 0.87%   |
| Kubuntu 20.04     | 16        | 0.73%   |
| BlackPanther 18.1 | 15        | 0.68%   |
| Debian 10         | 14        | 0.64%   |
| Xubuntu 18.04     | 13        | 0.59%   |
| Linux Mint 19.2   | 13        | 0.59%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 720       | 34.35%  |
| Linux Mint    | 178       | 8.49%   |
| Pop!_OS       | 146       | 6.97%   |
| Fedora        | 131       | 6.25%   |
| OpenMandriva  | 98        | 4.68%   |
| Manjaro       | 88        | 4.2%    |
| Zorin         | 85        | 4.06%   |
| Arch          | 67        | 3.2%    |
| Xubuntu       | 64        | 3.05%   |
| Debian        | 60        | 2.86%   |
| KDE neon      | 58        | 2.77%   |
| Kubuntu       | 42        | 2%      |
| ROSA          | 36        | 1.72%   |
| ArcoLinux     | 31        | 1.48%   |
| Kali          | 19        | 0.91%   |
| SteamOS       | 17        | 0.81%   |
| Lubuntu       | 17        | 0.81%   |
| Elementary    | 17        | 0.81%   |
| Gentoo        | 16        | 0.76%   |
| Endless       | 16        | 0.76%   |
| Clear Linux   | 16        | 0.76%   |
| BlackPanther  | 15        | 0.72%   |
| openSUSE      | 13        | 0.62%   |
| EndeavourOS   | 13        | 0.62%   |
| Ubuntu Budgie | 11        | 0.52%   |
| Ubuntu Unity  | 10        | 0.48%   |
| MX            | 10        | 0.48%   |
| Ubuntu MATE   | 8         | 0.38%   |
| Peppermint    | 8         | 0.38%   |
| LMDE          | 8         | 0.38%   |
| Garuda Linux  | 8         | 0.38%   |
| Parrot        | 5         | 0.24%   |
| CentOS        | 5         | 0.24%   |
| Alpine        | 5         | 0.24%   |
| Ubuntu Studio | 4         | 0.19%   |
| LinuxFX       | 4         | 0.19%   |
| Artix         | 4         | 0.19%   |
| Slackware     | 3         | 0.14%   |
| Siduction     | 3         | 0.14%   |
| Reborn OS     | 3         | 0.14%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 46        | 1.9%    |
| 5.4.0-42-generic         | 45        | 1.85%   |
| 5.11.0-27-generic        | 42        | 1.73%   |
| 5.16.7-desktop-1omv4003  | 35        | 1.44%   |
| 5.3.0-40-generic         | 27        | 1.11%   |
| 5.4.0-29-generic         | 23        | 0.95%   |
| 5.4.0-52-generic         | 21        | 0.87%   |
| 5.4.0-40-generic         | 21        | 0.87%   |
| 5.0.0-37-generic         | 21        | 0.87%   |
| 5.8.0-7630-generic       | 20        | 0.82%   |
| 5.4.0-58-generic         | 20        | 0.82%   |
| 5.3.0-46-generic         | 20        | 0.82%   |
| 5.4.0-48-generic         | 18        | 0.74%   |
| 5.4.0-45-generic         | 18        | 0.74%   |
| 5.4.0-37-generic         | 15        | 0.62%   |
| 5.4.0-26-generic         | 15        | 0.62%   |
| 5.13.0-7614-generic      | 15        | 0.62%   |
| 5.11.0-40-generic        | 15        | 0.62%   |
| 5.8.0-41-generic         | 14        | 0.58%   |
| 5.4.0-91-generic         | 14        | 0.58%   |
| 5.4.0-47-generic         | 14        | 0.58%   |
| 5.3.0-42-generic         | 14        | 0.58%   |
| 5.15.0-47-generic        | 14        | 0.58%   |
| 5.15.0-46-generic        | 14        | 0.58%   |
| 5.15.0-41-generic        | 14        | 0.58%   |
| 5.13.0-30-generic        | 14        | 0.58%   |
| 5.11.0-38-generic        | 14        | 0.58%   |
| 5.8.0-43-generic         | 13        | 0.54%   |
| 5.4.0-54-generic         | 13        | 0.54%   |
| 5.3.0-51-generic         | 13        | 0.54%   |
| 5.11.0-34-generic        | 13        | 0.54%   |
| 5.8.0-59-generic         | 12        | 0.49%   |
| 5.4.0-72-generic         | 12        | 0.49%   |
| 5.4.0-65-generic         | 12        | 0.49%   |
| 5.4.0-53-generic         | 12        | 0.49%   |
| 5.3.0-28-generic         | 12        | 0.49%   |
| 5.11.0-7620-generic      | 12        | 0.49%   |
| 5.0.0-32-generic         | 12        | 0.49%   |
| 5.0.0-25-generic         | 12        | 0.49%   |
| 5.4.0-88-generic         | 11        | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 454       | 19.98%  |
| 5.11.0  | 175       | 7.7%    |
| 5.8.0   | 146       | 6.43%   |
| 5.3.0   | 144       | 6.34%   |
| 5.13.0  | 142       | 6.25%   |
| 4.15.0  | 137       | 6.03%   |
| 5.0.0   | 87        | 3.83%   |
| 5.15.0  | 82        | 3.61%   |
| 5.10.0  | 49        | 2.16%   |
| 4.18.0  | 48        | 2.11%   |
| 5.10.14 | 47        | 2.07%   |
| 5.16.7  | 37        | 1.63%   |
| 4.19.0  | 22        | 0.97%   |
| 5.17.5  | 12        | 0.53%   |
| 5.14.0  | 12        | 0.53%   |
| 5.19.0  | 11        | 0.48%   |
| 5.15.5  | 11        | 0.48%   |
| 4.18.16 | 10        | 0.44%   |
| 5.9.16  | 9         | 0.4%    |
| 5.9.11  | 9         | 0.4%    |
| 5.15.11 | 9         | 0.4%    |
| 5.17.9  | 8         | 0.35%   |
| 5.16.0  | 8         | 0.35%   |
| 5.11.12 | 8         | 0.35%   |
| 4.9.60  | 8         | 0.35%   |
| 4.9.20  | 8         | 0.35%   |
| 5.18.0  | 7         | 0.31%   |
| 5.17.0  | 7         | 0.31%   |
| 5.15.15 | 7         | 0.31%   |
| 5.9.8   | 6         | 0.26%   |
| 5.8.16  | 6         | 0.26%   |
| 5.17.15 | 6         | 0.26%   |
| 5.16.13 | 6         | 0.26%   |
| 5.15.12 | 6         | 0.26%   |
| 5.13.13 | 6         | 0.26%   |
| 5.12.4  | 6         | 0.26%   |
| 5.9.14  | 5         | 0.22%   |
| 5.8.13  | 5         | 0.22%   |
| 5.8.12  | 5         | 0.22%   |
| 5.7.0   | 5         | 0.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 496       | 22.23%  |
| 5.11    | 200       | 8.96%   |
| 5.8     | 196       | 8.79%   |
| 5.13    | 162       | 7.26%   |
| 5.15    | 160       | 7.17%   |
| 5.3     | 153       | 6.86%   |
| 5.10    | 139       | 6.23%   |
| 4.15    | 138       | 6.19%   |
| 5.0     | 89        | 3.99%   |
| 5.16    | 87        | 3.9%    |
| 4.18    | 58        | 2.6%    |
| 5.17    | 45        | 2.02%   |
| 5.9     | 44        | 1.97%   |
| 5.14    | 34        | 1.52%   |
| 5.18    | 31        | 1.39%   |
| 5.12    | 31        | 1.39%   |
| 5.19    | 29        | 1.3%    |
| 4.19    | 29        | 1.3%    |
| 5.6     | 25        | 1.12%   |
| 4.9     | 24        | 1.08%   |
| 5.7     | 23        | 1.03%   |
| 5.5     | 13        | 0.58%   |
| 4.4     | 7         | 0.31%   |
| 3.10    | 3         | 0.13%   |
| 5.2     | 2         | 0.09%   |
| 5.1     | 2         | 0.09%   |
| 4.8     | 2         | 0.09%   |
| 4.20    | 2         | 0.09%   |
| 4.14    | 2         | 0.09%   |
| 4.1     | 2         | 0.09%   |
| 6.0     | 1         | 0.04%   |
| 4.16    | 1         | 0.04%   |
| 4.13    | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 1940      | 96.23%  |
| i686    | 73        | 3.62%   |
| armv7l  | 2         | 0.1%    |
| aarch64 | 1         | 0.05%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| GNOME                | 916       | 43.27%  |
| Unknown              | 301       | 14.22%  |
| KDE5                 | 292       | 13.79%  |
| XFCE                 | 172       | 8.12%   |
| X-Cinnamon           | 139       | 6.57%   |
| KDE                  | 75        | 3.54%   |
| MATE                 | 42        | 1.98%   |
| Cinnamon             | 28        | 1.32%   |
| KDE4                 | 25        | 1.18%   |
| LXQt                 | 19        | 0.9%    |
| i3                   | 18        | 0.85%   |
| Pantheon             | 16        | 0.76%   |
| Budgie               | 15        | 0.71%   |
| Unity                | 12        | 0.57%   |
| LXDE                 | 12        | 0.57%   |
| GNOME Flashback      | 9         | 0.43%   |
| DWM                  | 5         | 0.24%   |
| enlightenment        | 4         | 0.19%   |
| Deepin               | 4         | 0.19%   |
| qtile                | 3         | 0.14%   |
| GNOME Classic        | 2         | 0.09%   |
| awesome              | 2         | 0.09%   |
| wmaker-common        | 1         | 0.05%   |
| swayLANG=en_CA.UTF-8 | 1         | 0.05%   |
| sway                 | 1         | 0.05%   |
| spectrwm             | 1         | 0.05%   |
| hyprland             | 1         | 0.05%   |
| bspwm                | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 1656      | 79.73%  |
| Wayland | 233       | 11.22%  |
| Unknown | 167       | 8.04%   |
| Tty     | 21        | 1.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1213      | 57.57%  |
| SDDM    | 258       | 12.24%  |
| GDM     | 244       | 11.58%  |
| LightDM | 150       | 7.12%   |
| GDM3    | 136       | 6.45%   |
| TDM     | 74        | 3.51%   |
| KDM     | 24        | 1.14%   |
| XDM     | 5         | 0.24%   |
| Ly      | 2         | 0.09%   |
| LXDM    | 1         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_CA   | 1030      | 49.47%  |
| en_US   | 537       | 25.79%  |
| Unknown | 271       | 13.02%  |
| fr_CA   | 136       | 6.53%   |
| C       | 47        | 2.26%   |
| fr_FR   | 20        | 0.96%   |
| en_GB   | 10        | 0.48%   |
| pt_BR   | 3         | 0.14%   |
| POSIX   | 3         | 0.14%   |
| es_ES   | 3         | 0.14%   |
| en_AU   | 3         | 0.14%   |
| zh_CN   | 2         | 0.1%    |
| uk_UA   | 2         | 0.1%    |
| en_IN   | 2         | 0.1%    |
| C.UTF8  | 2         | 0.1%    |
| ru_RU   | 1         | 0.05%   |
| ro_RO   | 1         | 0.05%   |
| pl_PL   | 1         | 0.05%   |
| pa_IN   | 1         | 0.05%   |
| ga_IE   | 1         | 0.05%   |
| es_CL   | 1         | 0.05%   |
| en_ZA   | 1         | 0.05%   |
| en_NZ   | 1         | 0.05%   |
| en_FI   | 1         | 0.05%   |
| de_DE   | 1         | 0.05%   |
| co_FR   | 1         | 0.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 1088      | 52.82%  |
| EFI  | 972       | 47.18%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 1621      | 78.54%  |
| Overlay | 162       | 7.85%   |
| Btrfs   | 155       | 7.51%   |
| Unknown | 79        | 3.83%   |
| Zfs     | 18        | 0.87%   |
| Xfs     | 16        | 0.78%   |
| Ext2    | 8         | 0.39%   |
| Aufs    | 3         | 0.15%   |
| Tmpfs   | 1         | 0.05%   |
| Ext3    | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1294      | 62.91%  |
| GPT     | 575       | 27.95%  |
| MBR     | 188       | 9.14%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1803      | 88.12%  |
| Yes       | 243       | 11.88%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1556      | 75.98%  |
| Yes       | 492       | 24.02%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 414       | 20.56%  |
| Dell                           | 397       | 19.71%  |
| Hewlett-Packard                | 335       | 16.63%  |
| Acer                           | 220       | 10.92%  |
| ASUSTek Computer               | 210       | 10.43%  |
| Toshiba                        | 91        | 4.52%   |
| Apple                          | 76        | 3.77%   |
| MSI                            | 52        | 2.58%   |
| Sony                           | 31        | 1.54%   |
| Samsung Electronics            | 19        | 0.94%   |
| Valve                          | 16        | 0.79%   |
| Google                         | 16        | 0.79%   |
| Alienware                      | 15        | 0.74%   |
| System76                       | 14        | 0.7%    |
| Gateway                        | 14        | 0.7%    |
| Panasonic                      | 13        | 0.65%   |
| Unknown                        | 12        | 0.6%    |
| Razer                          | 6         | 0.3%    |
| Fujitsu                        | 6         | 0.3%    |
| HUAWEI                         | 5         | 0.25%   |
| Gigabyte Technology            | 5         | 0.25%   |
| Notebook                       | 4         | 0.2%    |
| LG Electronics                 | 4         | 0.2%    |
| EUROCOM                        | 3         | 0.15%   |
| eMachines                      | 3         | 0.15%   |
| Purism                         | 2         | 0.1%    |
| Motion Computing               | 2         | 0.1%    |
| Matsushita Electric Industrial | 2         | 0.1%    |
| Intel                          | 2         | 0.1%    |
| Getac                          | 2         | 0.1%    |
| Framework                      | 2         | 0.1%    |
| VIT                            | 1         | 0.05%   |
| Teclast                        | 1         | 0.05%   |
| RCA                            | 1         | 0.05%   |
| Pegatron                       | 1         | 0.05%   |
| Packard Bell                   | 1         | 0.05%   |
| OriginPC                       | 1         | 0.05%   |
| Mediacom                       | 1         | 0.05%   |
| Jumper                         | 1         | 0.05%   |
| Intel Client Systems           | 1         | 0.05%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| HP Notebook                            | 19        | 0.94%   |
| Unknown                                | 19        | 0.94%   |
| HP Pavilion g6                         | 18        | 0.89%   |
| Valve Jupiter                          | 16        | 0.79%   |
| Acer Aspire A315-21                    | 13        | 0.65%   |
| Dell XPS 15 7590                       | 12        | 0.6%    |
| Dell Latitude E6410                    | 12        | 0.6%    |
| Dell XPS 15 9500                       | 11        | 0.55%   |
| HP Pavilion 15                         | 10        | 0.5%    |
| Dell Latitude E6420                    | 10        | 0.5%    |
| HP Pavilion dv6                        | 9         | 0.45%   |
| HP EliteBook 8460p                     | 9         | 0.45%   |
| Toshiba Satellite A200                 | 8         | 0.4%    |
| HP Pavilion Notebook                   | 8         | 0.4%    |
| Dell Inspiron 1545                     | 8         | 0.4%    |
| Apple MacBookPro9,2                    | 8         | 0.4%    |
| Dell XPS 13 9310                       | 7         | 0.35%   |
| Dell Latitude E6540                    | 7         | 0.35%   |
| Dell Latitude E6430                    | 7         | 0.35%   |
| Dell Latitude D830                     | 7         | 0.35%   |
| Apple MacBookPro8,1                    | 7         | 0.35%   |
| Acer Aspire A315-42                    | 7         | 0.35%   |
| Acer Aspire 5742                       | 7         | 0.35%   |
| Toshiba Satellite C650                 | 6         | 0.3%    |
| HP Laptop 14-fq0xxx                    | 6         | 0.3%    |
| HP EliteBook 8470p                     | 6         | 0.3%    |
| HP EliteBook 840 G3                    | 6         | 0.3%    |
| HP 2000                                | 6         | 0.3%    |
| Dell XPS 15 9570                       | 6         | 0.3%    |
| Dell XPS 15 9560                       | 6         | 0.3%    |
| Dell XPS 13 9360                       | 6         | 0.3%    |
| Dell XPS 13 7390                       | 6         | 0.3%    |
| Dell Latitude E6440                    | 6         | 0.3%    |
| ASUS VivoBook_ASUSLaptop X571LH_K571LH | 6         | 0.3%    |
| System76 Galago Pro                    | 5         | 0.25%   |
| Lenovo Legion 5 15ARH05H 82B1          | 5         | 0.25%   |
| HP Stream Laptop 14-ax0XX              | 5         | 0.25%   |
| HP ProBook 6470b                       | 5         | 0.25%   |
| HP ProBook 4540s                       | 5         | 0.25%   |
| HP Pavilion dv6700                     | 5         | 0.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 284       | 14.1%   |
| Acer Aspire        | 176       | 8.74%   |
| Dell Latitude      | 131       | 6.5%    |
| Dell Inspiron      | 109       | 5.41%   |
| HP Pavilion        | 95        | 4.72%   |
| Dell XPS           | 88        | 4.37%   |
| Toshiba Satellite  | 78        | 3.87%   |
| Lenovo IdeaPad     | 65        | 3.23%   |
| HP EliteBook       | 65        | 3.23%   |
| HP Laptop          | 44        | 2.18%   |
| HP ProBook         | 36        | 1.79%   |
| ASUS VivoBook      | 34        | 1.69%   |
| Dell Precision     | 24        | 1.19%   |
| ASUS ROG           | 21        | 1.04%   |
| HP Notebook        | 19        | 0.94%   |
| Unknown            | 19        | 0.94%   |
| Valve Jupiter      | 16        | 0.79%   |
| Dell Vostro        | 15        | 0.74%   |
| Acer Swift         | 15        | 0.74%   |
| Lenovo Legion      | 14        | 0.7%    |
| HP ENVY            | 14        | 0.7%    |
| Acer Nitro         | 12        | 0.6%    |
| HP Stream          | 11        | 0.55%   |
| HP Compaq          | 11        | 0.55%   |
| ASUS TUF           | 11        | 0.55%   |
| Dell Studio        | 10        | 0.5%    |
| Apple MacBookPro9  | 10        | 0.5%    |
| Apple MacBookPro8  | 10        | 0.5%    |
| Dell System        | 8         | 0.4%    |
| ASUS ZenBook       | 8         | 0.4%    |
| Apple MacBookPro11 | 8         | 0.4%    |
| Lenovo ThinkBook   | 7         | 0.35%   |
| ASUS ASUS          | 7         | 0.35%   |
| Apple MacBookPro5  | 7         | 0.35%   |
| HP Presario        | 6         | 0.3%    |
| HP 2000            | 6         | 0.3%    |
| ASUS Strix         | 6         | 0.3%    |
| Toshiba TECRA      | 5         | 0.25%   |
| Toshiba PORTEGE    | 5         | 0.25%   |
| System76 Galago    | 5         | 0.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 192       | 9.53%   |
| 2012    | 181       | 8.99%   |
| 2020    | 179       | 8.89%   |
| 2019    | 158       | 7.85%   |
| 2018    | 154       | 7.65%   |
| 2013    | 145       | 7.2%    |
| 2017    | 138       | 6.85%   |
| 2010    | 132       | 6.55%   |
| 2014    | 117       | 5.81%   |
| 2016    | 108       | 5.36%   |
| 2015    | 103       | 5.11%   |
| 2008    | 100       | 4.97%   |
| 2021    | 90        | 4.47%   |
| 2009    | 75        | 3.72%   |
| 2007    | 71        | 3.53%   |
| 2022    | 34        | 1.69%   |
| 2006    | 23        | 1.14%   |
| 2005    | 8         | 0.4%    |
| Unknown | 4         | 0.2%    |
| 2004    | 2         | 0.1%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 2014      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1866      | 91.97%  |
| Enabled  | 163       | 8.03%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1986      | 98.61%  |
| Yes  | 28        | 1.39%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 624       | 30.56%  |
| 3.01-4.0    | 409       | 20.03%  |
| 8.01-16.0   | 370       | 18.12%  |
| 16.01-24.0  | 334       | 16.36%  |
| 32.01-64.0  | 119       | 5.83%   |
| 1.01-2.0    | 99        | 4.85%   |
| 2.01-3.0    | 41        | 2.01%   |
| 64.01-256.0 | 17        | 0.83%   |
| 0.51-1.0    | 16        | 0.78%   |
| 24.01-32.0  | 11        | 0.54%   |
| 0.01-0.5    | 2         | 0.1%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 856       | 38.3%   |
| 2.01-3.0   | 549       | 24.56%  |
| 4.01-8.0   | 290       | 12.98%  |
| 3.01-4.0   | 280       | 12.53%  |
| 0.51-1.0   | 150       | 6.71%   |
| 8.01-16.0  | 68        | 3.04%   |
| 0.01-0.5   | 31        | 1.39%   |
| 24.01-32.0 | 5         | 0.22%   |
| 16.01-24.0 | 4         | 0.18%   |
| 32.01-64.0 | 1         | 0.04%   |
| Unknown    | 1         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1504      | 72.76%  |
| 2      | 457       | 22.11%  |
| 3      | 75        | 3.63%   |
| 0      | 19        | 0.92%   |
| 4      | 10        | 0.48%   |
| 7      | 1         | 0.05%   |
| 5      | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1193      | 58.88%  |
| Yes       | 833       | 41.12%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1686      | 83.38%  |
| No        | 336       | 16.62%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1972      | 97.82%  |
| No        | 44        | 2.18%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1466      | 71.58%  |
| No        | 582       | 28.42%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Canada  | 2014      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Notebooks | Percent |
|-----------------|-----------|---------|
| Toronto         | 209       | 9.88%   |
| Montreal        | 201       | 9.5%    |
| Vancouver       | 89        | 4.21%   |
| Calgary         | 80        | 3.78%   |
| Edmonton        | 72        | 3.4%    |
| Ottawa          | 70        | 3.31%   |
| Québec         | 52        | 2.46%   |
| Winnipeg        | 48        | 2.27%   |
| Mississauga     | 42        | 1.99%   |
| Victoria        | 39        | 1.84%   |
| Regina          | 29        | 1.37%   |
| London          | 27        | 1.28%   |
| Surrey          | 25        | 1.18%   |
| Laval           | 25        | 1.18%   |
| Brampton        | 23        | 1.09%   |
| Kitchener       | 21        | 0.99%   |
| Hamilton        | 20        | 0.95%   |
| Burnaby         | 18        | 0.85%   |
| Halifax         | 16        | 0.76%   |
| Saskatoon       | 15        | 0.71%   |
| Gatineau        | 14        | 0.66%   |
| Windsor         | 13        | 0.61%   |
| Scarborough     | 13        | 0.61%   |
| Oshawa          | 13        | 0.61%   |
| Moncton         | 13        | 0.61%   |
| Markham         | 13        | 0.61%   |
| Sherbrooke      | 12        | 0.57%   |
| Richmond        | 12        | 0.57%   |
| New Westminster | 12        | 0.57%   |
| Richmond Hill   | 11        | 0.52%   |
| Levis           | 11        | 0.52%   |
| Kingston        | 11        | 0.52%   |
| Fredericton     | 10        | 0.47%   |
| Vernon          | 9         | 0.43%   |
| Trois-Rivières | 9         | 0.43%   |
| Thunder Bay     | 9         | 0.43%   |
| Kelowna         | 9         | 0.43%   |
| Barrie          | 9         | 0.43%   |
| Waterloo        | 8         | 0.38%   |
| St. Catharines  | 8         | 0.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 361       | 501    | 14.59%  |
| WDC                 | 357       | 443    | 14.42%  |
| Seagate             | 316       | 410    | 12.77%  |
| Toshiba             | 216       | 264    | 8.73%   |
| Kingston            | 158       | 207    | 6.38%   |
| Unknown             | 152       | 192    | 6.14%   |
| SanDisk             | 117       | 143    | 4.73%   |
| Intel               | 93        | 142    | 3.76%   |
| Hitachi             | 93        | 105    | 3.76%   |
| SK hynix            | 87        | 111    | 3.52%   |
| HGST                | 77        | 92     | 3.11%   |
| Crucial             | 55        | 66     | 2.22%   |
| A-DATA Technology   | 41        | 52     | 1.66%   |
| Micron Technology   | 38        | 53     | 1.54%   |
| Apple               | 37        | 40     | 1.49%   |
| Fujitsu             | 34        | 37     | 1.37%   |
| LITEONIT            | 18        | 18     | 0.73%   |
| KIOXIA              | 18        | 22     | 0.73%   |
| SPCC                | 15        | 18     | 0.61%   |
| China               | 13        | 13     | 0.53%   |
| LITEON              | 12        | 14     | 0.48%   |
| Phison              | 10        | 11     | 0.4%    |
| PNY                 | 9         | 16     | 0.36%   |
| OCZ                 | 8         | 8      | 0.32%   |
| Dogfish             | 6         | 7      | 0.24%   |
| ASMT                | 6         | 6      | 0.24%   |
| Team                | 5         | 7      | 0.2%    |
| Silicon Motion      | 5         | 5      | 0.2%    |
| Mushkin             | 5         | 7      | 0.2%    |
| KingFast            | 5         | 7      | 0.2%    |
| JMicron Technology  | 5         | 5      | 0.2%    |
| Unknown             | 5         | 5      | 0.2%    |
| TO Exter            | 4         | 5      | 0.16%   |
| Patriot             | 4         | 4      | 0.16%   |
| Corsair             | 4         | 4      | 0.16%   |
| XPG                 | 3         | 3      | 0.12%   |
| Transcend           | 3         | 4      | 0.12%   |
| OWC                 | 3         | 5      | 0.12%   |
| Maxone              | 3         | 3      | 0.12%   |
| Lite-On             | 3         | 6      | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD    | 39        | 1.51%   |
| Toshiba MQ01ABD100 1TB             | 35        | 1.36%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 34        | 1.32%   |
| Seagate ST1000LM035-1RK172 1TB     | 29        | 1.13%   |
| Unknown MMC Card  64GB             | 27        | 1.05%   |
| Unknown MMC Card  32GB             | 26        | 1.01%   |
| HGST HTS721010A9E630 1TB           | 26        | 1.01%   |
| Samsung NVMe SSD Drive 512GB       | 20        | 0.78%   |
| Samsung SSD 860 EVO 500GB          | 19        | 0.74%   |
| Intel NVMe SSD Drive 512GB         | 19        | 0.74%   |
| Seagate ST500LT012-1DG142 500GB    | 18        | 0.7%    |
| Seagate ST1000LX015-1U7172 1TB     | 18        | 0.7%    |
| Kingston SA400S37120G 120GB SSD    | 18        | 0.7%    |
| WDC WD10SPZX-21Z10T0 1TB           | 16        | 0.62%   |
| SK hynix NVMe SSD Drive 512GB      | 16        | 0.62%   |
| Seagate ST9500325AS 500GB          | 16        | 0.62%   |
| Samsung SSD 860 EVO 1TB            | 16        | 0.62%   |
| Unknown MMC Card  16GB             | 15        | 0.58%   |
| Samsung SSD 850 EVO 250GB          | 15        | 0.58%   |
| Kingston SA400S37480G 480GB SSD    | 15        | 0.58%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 14        | 0.54%   |
| Samsung NVMe SSD Drive 256GB       | 14        | 0.54%   |
| HGST HTS725050A7E630 500GB         | 14        | 0.54%   |
| WDC WD10JPVX-22JC3T0 1TB           | 13        | 0.5%    |
| Seagate ST500LM021-1KJ152 500GB    | 13        | 0.5%    |
| SanDisk NVMe SSD Drive 512GB       | 13        | 0.5%    |
| Samsung NVMe SSD Drive 500GB       | 13        | 0.5%    |
| Kingston SV300S37A120G 120GB SSD   | 13        | 0.5%    |
| Toshiba MQ04ABF100 1TB             | 12        | 0.47%   |
| Seagate Expansion 1TB              | 12        | 0.47%   |
| Samsung SSD 860 EVO 250GB          | 12        | 0.47%   |
| Samsung SSD 850 EVO 500GB          | 12        | 0.47%   |
| HGST HTS541010A9E680 1TB           | 12        | 0.47%   |
| Crucial CT1000MX500SSD1 1TB        | 12        | 0.47%   |
| Toshiba MQ01ABF050 500GB           | 11        | 0.43%   |
| SanDisk NVMe SSD Drive 500GB       | 11        | 0.43%   |
| WDC WDS100T2B0A-00SM50 1TB SSD     | 10        | 0.39%   |
| Toshiba MQ01ABD075 752GB           | 10        | 0.39%   |
| Seagate ST9500420AS 500GB          | 10        | 0.39%   |
| Hitachi HTS547575A9E384 752GB      | 10        | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 305       | 391    | 32.04%  |
| WDC                 | 236       | 278    | 24.79%  |
| Toshiba             | 170       | 215    | 17.86%  |
| Hitachi             | 93        | 105    | 9.77%   |
| HGST                | 77        | 92     | 8.09%   |
| Fujitsu             | 34        | 37     | 3.57%   |
| Samsung Electronics | 14        | 16     | 1.47%   |
| Apple               | 8         | 8      | 0.84%   |
| Unknown             | 7         | 8      | 0.74%   |
| Maxone              | 3         | 3      | 0.32%   |
| USB 3.0             | 1         | 2      | 0.11%   |
| Inateck             | 1         | 1      | 0.11%   |
| Generic-            | 1         | 1      | 0.11%   |
| DAS                 | 1         | 5      | 0.11%   |
| ASMT                | 1         | 1      | 0.11%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 196       | 274    | 24.59%  |
| Kingston            | 134       | 171    | 16.81%  |
| SanDisk             | 67        | 78     | 8.41%   |
| WDC                 | 56        | 80     | 7.03%   |
| Crucial             | 51        | 62     | 6.4%    |
| A-DATA Technology   | 35        | 45     | 4.39%   |
| Intel               | 34        | 48     | 4.27%   |
| Micron Technology   | 26        | 41     | 3.26%   |
| Apple               | 24        | 24     | 3.01%   |
| LITEONIT            | 18        | 18     | 2.26%   |
| Toshiba             | 15        | 17     | 1.88%   |
| SK hynix            | 15        | 21     | 1.88%   |
| SPCC                | 14        | 17     | 1.76%   |
| China               | 13        | 13     | 1.63%   |
| PNY                 | 9         | 16     | 1.13%   |
| LITEON              | 9         | 10     | 1.13%   |
| OCZ                 | 8         | 8      | 1%      |
| Dogfish             | 6         | 7      | 0.75%   |
| Seagate             | 5         | 6      | 0.63%   |
| TO Exter            | 4         | 5      | 0.5%    |
| Team                | 4         | 6      | 0.5%    |
| Patriot             | 4         | 4      | 0.5%    |
| Mushkin             | 4         | 6      | 0.5%    |
| ASMT                | 4         | 4      | 0.5%    |
| Transcend           | 3         | 4      | 0.38%   |
| KingSpec            | 3         | 5      | 0.38%   |
| Corsair             | 3         | 3      | 0.38%   |
| WDC WDS             | 2         | 2      | 0.25%   |
| OWC                 | 2         | 4      | 0.25%   |
| NGFF                | 2         | 2      | 0.25%   |
| KingFast            | 2         | 2      | 0.25%   |
| KingDian            | 2         | 2      | 0.25%   |
| BHT                 | 2         | 2      | 0.25%   |
| AMD                 | 2         | 3      | 0.25%   |
| Vaseky              | 1         | 1      | 0.13%   |
| TYPEC 1T            | 1         | 2      | 0.13%   |
| TSA                 | 1         | 1      | 0.13%   |
| TCSUNBOW            | 1         | 2      | 0.13%   |
| SPCC Sol            | 1         | 2      | 0.13%   |
| ShanDianZhe         | 1         | 2      | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 921       | 1163   | 39.24%  |
| SSD     | 724       | 1035   | 30.85%  |
| NVMe    | 524       | 729    | 22.33%  |
| MMC     | 145       | 184    | 6.18%   |
| Unknown | 33        | 41     | 1.41%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1505      | 2096   | 66.18%  |
| NVMe | 518       | 720    | 22.78%  |
| MMC  | 145       | 184    | 6.38%   |
| SAS  | 106       | 152    | 4.66%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1092      | 1471   | 66.79%  |
| 0.51-1.0   | 496       | 662    | 30.34%  |
| 1.01-2.0   | 35        | 49     | 2.14%   |
| 3.01-4.0   | 7         | 8      | 0.43%   |
| 4.01-10.0  | 5         | 8      | 0.31%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 578       | 27%     |
| 251-500        | 577       | 26.95%  |
| 501-1000       | 344       | 16.07%  |
| 1-20           | 183       | 8.55%   |
| 51-100         | 150       | 7.01%   |
| 1001-2000      | 101       | 4.72%   |
| 21-50          | 91        | 4.25%   |
| Unknown        | 56        | 2.62%   |
| More than 3000 | 35        | 1.63%   |
| 2001-3000      | 26        | 1.21%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 976       | 44.1%   |
| 21-50          | 414       | 18.71%  |
| 101-250        | 267       | 12.07%  |
| 51-100         | 255       | 11.52%  |
| 251-500        | 145       | 6.55%   |
| 501-1000       | 64        | 2.89%   |
| Unknown        | 56        | 2.53%   |
| 1001-2000      | 23        | 1.04%   |
| More than 3000 | 9         | 0.41%   |
| 2001-3000      | 4         | 0.18%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB  | 5         | 6      | 4.46%   |
| Toshiba MQ01ABD100 1TB              | 4         | 5      | 3.57%   |
| Seagate ST9500325AS 500GB           | 4         | 4      | 3.57%   |
| Seagate ST500LM000-1EJ162 500GB     | 4         | 4      | 3.57%   |
| HGST HTS541010A9E680 1TB            | 4         | 4      | 3.57%   |
| Seagate ST500LT012-9WS142 500GB     | 3         | 3      | 2.68%   |
| HGST HTS721010A9E630 1TB            | 3         | 3      | 2.68%   |
| HGST HTS545050A7E680 500GB          | 3         | 3      | 2.68%   |
| Toshiba MQ01ABD075 752GB            | 2         | 2      | 1.79%   |
| Toshiba MK2552GSX 250GB             | 2         | 2      | 1.79%   |
| Toshiba MK2035GSS 200GB             | 2         | 2      | 1.79%   |
| Seagate ST9500420AS 500GB           | 2         | 2      | 1.79%   |
| Seagate ST9320325AS 320GB           | 2         | 2      | 1.79%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 2         | 2      | 1.79%   |
| Seagate ST320LT020-9YG142 320GB     | 2         | 2      | 1.79%   |
| Seagate ST1000LX015-1U7172-SSHD 1TB | 2         | 2      | 1.79%   |
| Seagate ST1000LM035-1RK172 1TB      | 2         | 2      | 1.79%   |
| Hitachi HTS547575A9E384 752GB       | 2         | 2      | 1.79%   |
| Hitachi HTS545050B9A300 500GB       | 2         | 2      | 1.79%   |
| A-DATA Technology SX900 256GB SSD   | 2         | 2      | 1.79%   |
| WDC WD7500BPKT-60PK4T0 752GB        | 1         | 1      | 0.89%   |
| WDC WD5000LPVX-75V0TT0 500GB        | 1         | 1      | 0.89%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 1         | 1      | 0.89%   |
| WDC WD3200LPVX-22V0TT0 320GB        | 1         | 1      | 0.89%   |
| WDC WD2500BEVT-75A23T0 250GB        | 1         | 1      | 0.89%   |
| WDC WD2500BEVT-00ZCT0 250GB         | 1         | 1      | 0.89%   |
| WDC WD10JPVX-22JC3T0 1TB            | 1         | 1      | 0.89%   |
| WDC WD10JPVX-08JC3T5 1TB            | 1         | 1      | 0.89%   |
| WDC WD10JPVT-55A1YT0 1TB            | 1         | 1      | 0.89%   |
| WDC WD10EZEX-08M2NA0 1TB            | 1         | 2      | 0.89%   |
| Toshiba MK7575GSX 752GB             | 1         | 1      | 0.89%   |
| Toshiba MK6465GSXN 640GB            | 1         | 1      | 0.89%   |
| Toshiba MK6465GSX 640GB             | 1         | 1      | 0.89%   |
| Toshiba MK5076GSX 500GB             | 1         | 1      | 0.89%   |
| Toshiba MK5061GSY 500GB             | 1         | 1      | 0.89%   |
| Toshiba MK3265GSX 320GB             | 1         | 1      | 0.89%   |
| SK hynix SC311 SATA 256GB SSD       | 1         | 1      | 0.89%   |
| Seagate ST9750420AS 752GB           | 1         | 1      | 0.89%   |
| Seagate ST9320423AS 320GB           | 1         | 1      | 0.89%   |
| Seagate ST500LT012-1DG142 500GB     | 1         | 1      | 0.89%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 36        | 37     | 32.14%  |
| Toshiba             | 16        | 17     | 14.29%  |
| Hitachi             | 15        | 15     | 13.39%  |
| HGST                | 12        | 12     | 10.71%  |
| WDC                 | 10        | 11     | 8.93%   |
| Samsung Electronics | 4         | 4      | 3.57%   |
| A-DATA Technology   | 4         | 4      | 3.57%   |
| Intel               | 3         | 3      | 2.68%   |
| Kingston            | 2         | 2      | 1.79%   |
| SK hynix            | 1         | 1      | 0.89%   |
| OCZ                 | 1         | 1      | 0.89%   |
| Micron Technology   | 1         | 1      | 0.89%   |
| LITEONIT            | 1         | 1      | 0.89%   |
| LITEON              | 1         | 1      | 0.89%   |
| Fujitsu             | 1         | 1      | 0.89%   |
| Crucial             | 1         | 1      | 0.89%   |
| Corsair             | 1         | 1      | 0.89%   |
| ASMT                | 1         | 1      | 0.89%   |
| Apple               | 1         | 1      | 0.89%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 36        | 37     | 39.13%  |
| Toshiba             | 16        | 17     | 17.39%  |
| Hitachi             | 15        | 15     | 16.3%   |
| HGST                | 12        | 12     | 13.04%  |
| WDC                 | 10        | 11     | 10.87%  |
| Samsung Electronics | 1         | 1      | 1.09%   |
| Fujitsu             | 1         | 1      | 1.09%   |
| Apple               | 1         | 1      | 1.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 92        | 95     | 82.14%  |
| SSD  | 18        | 18     | 16.07%  |
| NVMe | 2         | 2      | 1.79%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                  | Notebooks | Drives | Percent |
|------------------------|-----------|--------|---------|
| LITEON CA3-8D512 512GB | 1         | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| LITEON | 1         | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1355      | 2141   | 63.95%  |
| Works    | 652       | 894    | 30.77%  |
| Malfunc  | 111       | 115    | 5.24%   |
| Failed   | 1         | 2      | 0.05%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 1375      | 60.98%  |
| AMD                            | 323       | 14.32%  |
| Samsung Electronics            | 186       | 8.25%   |
| SanDisk                        | 111       | 4.92%   |
| SK hynix                       | 72        | 3.19%   |
| Toshiba America Info Systems   | 32        | 1.42%   |
| Nvidia                         | 26        | 1.15%   |
| Kingston Technology Company    | 26        | 1.15%   |
| KIOXIA                         | 21        | 0.93%   |
| Phison Electronics             | 14        | 0.62%   |
| Micron Technology              | 12        | 0.53%   |
| ADATA Technology               | 8         | 0.35%   |
| Silicon Motion                 | 7         | 0.31%   |
| Lite-On Technology             | 6         | 0.27%   |
| Micron/Crucial Technology      | 5         | 0.22%   |
| Union Memory (Shenzhen)        | 4         | 0.18%   |
| Realtek Semiconductor          | 4         | 0.18%   |
| Marvell Technology Group       | 4         | 0.18%   |
| ASMedia Technology             | 4         | 0.18%   |
| Lenovo                         | 3         | 0.13%   |
| JMicron Technology             | 3         | 0.13%   |
| Apple                          | 3         | 0.13%   |
| Unknown                        | 2         | 0.09%   |
| Seagate Technology             | 2         | 0.09%   |
| Solid State Storage Technology | 1         | 0.04%   |
| Shenzhen Longsys Electronics   | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 261       | 10.67%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 177       | 7.24%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 137       | 5.6%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 124       | 5.07%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 115       | 4.7%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 93        | 3.8%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 90        | 3.68%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 74        | 3.03%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 73        | 2.98%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 70        | 2.86%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 64        | 2.62%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 53        | 2.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 52        | 2.13%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 51        | 2.09%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 42        | 1.72%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 40        | 1.64%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 39        | 1.59%   |
| Intel Volume Management Device NVMe RAID Controller                              | 31        | 1.27%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 29        | 1.19%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 27        | 1.1%    |
| Samsung NVMe SSD Controller 980                                                  | 27        | 1.1%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 27        | 1.1%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 26        | 1.06%   |
| Intel Non-Volatile memory controller                                             | 26        | 1.06%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 22        | 0.9%    |
| SK hynix Non-Volatile memory controller                                          | 20        | 0.82%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 18        | 0.74%   |
| SK hynix Gold P31 SSD                                                            | 17        | 0.7%    |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 17        | 0.7%    |
| Intel SSD 660P Series                                                            | 17        | 0.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 17        | 0.7%    |
| SanDisk Non-Volatile memory controller                                           | 16        | 0.65%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 16        | 0.65%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 15        | 0.61%   |
| SK hynix BC511                                                                   | 15        | 0.61%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 15        | 0.61%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 14        | 0.57%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 14        | 0.57%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 12        | 0.49%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 12        | 0.49%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1449      | 62.22%  |
| NVMe | 519       | 22.28%  |
| IDE  | 187       | 8.03%   |
| RAID | 174       | 7.47%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 1599      | 79.39%  |
| AMD     | 412       | 20.46%  |
| ARM     | 2         | 0.1%    |
| Unknown | 1         | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz             | 37        | 1.84%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 33        | 1.64%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 31        | 1.54%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 30        | 1.49%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 29        | 1.44%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 27        | 1.34%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 25        | 1.24%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 24        | 1.19%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 24        | 1.19%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 24        | 1.19%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 21        | 1.04%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 20        | 0.99%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 19        | 0.94%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 18        | 0.89%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 18        | 0.89%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 17        | 0.84%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 17        | 0.84%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 16        | 0.79%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 16        | 0.79%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 16        | 0.79%   |
| AMD Custom APU 0405                           | 16        | 0.79%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 14        | 0.69%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 14        | 0.69%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 14        | 0.69%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 14        | 0.69%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 13        | 0.65%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 13        | 0.65%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 11        | 0.55%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 11        | 0.55%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 11        | 0.55%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 11        | 0.55%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 11        | 0.55%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 11        | 0.55%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 11        | 0.55%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 10        | 0.5%    |
| Intel Core i7-6500U CPU @ 2.50GHz             | 10        | 0.5%    |
| Intel Core i7-5500U CPU @ 2.40GHz             | 10        | 0.5%    |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 10        | 0.5%    |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 10        | 0.5%    |
| Intel Core i5-3337U CPU @ 1.80GHz             | 10        | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 504       | 25.01%  |
| Intel Core i7           | 499       | 24.76%  |
| Intel Core 2 Duo        | 126       | 6.25%   |
| Intel Core i3           | 119       | 5.91%   |
| Other                   | 116       | 5.76%   |
| Intel Celeron           | 72        | 3.57%   |
| AMD Ryzen 7             | 59        | 2.93%   |
| AMD A6                  | 49        | 2.43%   |
| Intel Pentium           | 48        | 2.38%   |
| AMD Ryzen 5             | 44        | 2.18%   |
| Intel Atom              | 36        | 1.79%   |
| AMD A10                 | 34        | 1.69%   |
| Intel Pentium Dual-Core | 27        | 1.34%   |
| AMD A4                  | 24        | 1.19%   |
| Intel Pentium Dual      | 23        | 1.14%   |
| Intel Genuine           | 20        | 0.99%   |
| AMD A8                  | 18        | 0.89%   |
| AMD Ryzen 3             | 16        | 0.79%   |
| Intel Core i9           | 13        | 0.65%   |
| Intel Core 2            | 12        | 0.6%    |
| AMD Ryzen 9             | 12        | 0.6%    |
| AMD E2                  | 12        | 0.6%    |
| AMD E1                  | 11        | 0.55%   |
| AMD E                   | 11        | 0.55%   |
| AMD Turion 64 X2 Mobile | 9         | 0.45%   |
| AMD Athlon X2           | 8         | 0.4%    |
| AMD Ryzen 5 PRO         | 7         | 0.35%   |
| AMD A12                 | 7         | 0.35%   |
| Intel Xeon              | 6         | 0.3%    |
| Intel Pentium Silver    | 6         | 0.3%    |
| AMD C-50                | 5         | 0.25%   |
| AMD Athlon 64 X2        | 5         | 0.25%   |
| Intel Pentium M         | 4         | 0.2%    |
| AMD Turion 64 Mobile    | 4         | 0.2%    |
| AMD Ryzen 7 PRO         | 4         | 0.2%    |
| AMD Phenom II           | 4         | 0.2%    |
| Intel Core m3           | 3         | 0.15%   |
| Intel Celeron M         | 3         | 0.15%   |
| AMD V140                | 3         | 0.15%   |
| AMD Athlon II           | 3         | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1113      | 55.18%  |
| 4      | 600       | 29.75%  |
| 6      | 133       | 6.59%   |
| 8      | 102       | 5.06%   |
| 1      | 57        | 2.83%   |
| 14     | 8         | 0.4%    |
| 16     | 1         | 0.05%   |
| 10     | 1         | 0.05%   |
| 7      | 1         | 0.05%   |
| 3      | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2014      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1431      | 70.95%  |
| 1      | 586       | 29.05%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1955      | 96.78%  |
| 32-bit         | 34        | 1.68%   |
| Unknown        | 30        | 1.49%   |
| 64-bit         | 1         | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 474       | 22.76%  |
| 0x306a9    | 140       | 6.72%   |
| 0x206a7    | 133       | 6.39%   |
| 0x1067a    | 75        | 3.6%    |
| 0x40651    | 71        | 3.41%   |
| 0x906ea    | 66        | 3.17%   |
| 0x20655    | 62        | 2.98%   |
| 0x806ea    | 60        | 2.88%   |
| 0x306c3    | 52        | 2.5%    |
| 0x406e3    | 50        | 2.4%    |
| 0x306d4    | 49        | 2.35%   |
| 0x806e9    | 48        | 2.3%    |
| 0x6fd      | 46        | 2.21%   |
| 0xa0652    | 42        | 2.02%   |
| 0x806ec    | 38        | 1.82%   |
| 0x20652    | 34        | 1.63%   |
| 0x06001119 | 29        | 1.39%   |
| 0x806c1    | 28        | 1.34%   |
| 0x906e9    | 26        | 1.25%   |
| 0x30678    | 23        | 1.1%    |
| 0x706e5    | 21        | 1.01%   |
| 0x10676    | 21        | 1.01%   |
| 0x08108102 | 21        | 1.01%   |
| 0x06006705 | 21        | 1.01%   |
| 0x506e3    | 20        | 0.96%   |
| 0x0a50000c | 18        | 0.86%   |
| 0x406c4    | 17        | 0.82%   |
| 0x07030105 | 17        | 0.82%   |
| 0x05000119 | 17        | 0.82%   |
| 0x03000027 | 17        | 0.82%   |
| 0x806eb    | 16        | 0.77%   |
| 0x406c3    | 16        | 0.77%   |
| 0x106e5    | 15        | 0.72%   |
| 0x08600104 | 15        | 0.72%   |
| 0x6e8      | 13        | 0.62%   |
| 0x010000c8 | 13        | 0.62%   |
| 0x08108109 | 12        | 0.58%   |
| 0x6fb      | 11        | 0.53%   |
| 0x106c2    | 11        | 0.53%   |
| 0x706a1    | 10        | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 327       | 16.22%  |
| IvyBridge        | 179       | 8.88%   |
| Haswell          | 155       | 7.69%   |
| SandyBridge      | 153       | 7.59%   |
| Penryn           | 113       | 5.61%   |
| Westmere         | 112       | 5.56%   |
| Skylake          | 90        | 4.46%   |
| Core             | 86        | 4.27%   |
| Silvermont       | 69        | 3.42%   |
| Excavator        | 64        | 3.17%   |
| Broadwell        | 64        | 3.17%   |
| CometLake        | 59        | 2.93%   |
| Zen+             | 47        | 2.33%   |
| Unknown          | 47        | 2.33%   |
| Zen 2            | 45        | 2.23%   |
| TigerLake        | 44        | 2.18%   |
| Piledriver       | 36        | 1.79%   |
| IceLake          | 32        | 1.59%   |
| Puma             | 30        | 1.49%   |
| Zen 3            | 29        | 1.44%   |
| Bobcat           | 27        | 1.34%   |
| K8 Hammer        | 24        | 1.19%   |
| P6               | 23        | 1.14%   |
| K10 Llano        | 22        | 1.09%   |
| Nehalem          | 20        | 0.99%   |
| Bonnell          | 19        | 0.94%   |
| Zen              | 18        | 0.89%   |
| Goldmont plus    | 18        | 0.89%   |
| Jaguar           | 17        | 0.84%   |
| K10              | 14        | 0.69%   |
| Goldmont         | 12        | 0.6%    |
| K8 & K10 hybrid  | 10        | 0.5%    |
| Alderlake Hybrid | 7         | 0.35%   |
| Steamroller      | 2         | 0.1%    |
| Tremont          | 1         | 0.05%   |
| NetBurst         | 1         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 1427      | 58.17%  |
| Nvidia | 518       | 21.12%  |
| AMD    | 508       | 20.71%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 156       | 6.08%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 136       | 5.3%    |
| Intel Core Processor Integrated Graphics Controller                                      | 93        | 3.63%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 87        | 3.39%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 83        | 3.24%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 81        | 3.16%   |
| Intel UHD Graphics 620                                                                   | 74        | 2.88%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 63        | 2.46%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 59        | 2.3%    |
| Intel HD Graphics 5500                                                                   | 53        | 2.07%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 53        | 2.07%   |
| Intel HD Graphics 620                                                                    | 52        | 2.03%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 49        | 1.91%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 49        | 1.91%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 48        | 1.87%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 43        | 1.68%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 42        | 1.64%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 40        | 1.56%   |
| AMD Renoir                                                                               | 40        | 1.56%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 39        | 1.52%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 31        | 1.21%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 29        | 1.13%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 29        | 1.13%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 28        | 1.09%   |
| Intel HD Graphics 630                                                                    | 28        | 1.09%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 25        | 0.97%   |
| AMD Cezanne                                                                              | 25        | 0.97%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 21        | 0.82%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 20        | 0.78%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 20        | 0.78%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 20        | 0.78%   |
| Intel HD Graphics 530                                                                    | 19        | 0.74%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 18        | 0.7%    |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 17        | 0.66%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 16        | 0.62%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 16        | 0.62%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 15        | 0.58%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 15        | 0.58%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 14        | 0.55%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 13        | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 1024      | 50.67%  |
| 1 x AMD            | 387       | 19.15%  |
| Intel + Nvidia     | 346       | 17.12%  |
| 1 x Nvidia         | 133       | 6.58%   |
| Intel + AMD        | 54        | 2.67%   |
| AMD + Nvidia       | 38        | 1.88%   |
| 2 x AMD            | 30        | 1.48%   |
| Other              | 5         | 0.25%   |
| 2 x Nvidia         | 3         | 0.15%   |
| Intel + 2 x Nvidia | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1726      | 84.48%  |
| Proprietary | 269       | 13.17%  |
| Unknown     | 48        | 2.35%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1288      | 61.98%  |
| 0.01-0.5   | 307       | 14.77%  |
| 1.01-2.0   | 203       | 9.77%   |
| 0.51-1.0   | 104       | 5%      |
| 3.01-4.0   | 103       | 4.96%   |
| 5.01-6.0   | 34        | 1.64%   |
| 7.01-8.0   | 28        | 1.35%   |
| 2.01-3.0   | 7         | 0.34%   |
| 8.01-16.0  | 4         | 0.19%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 446       | 19.07%  |
| LG Display              | 338       | 14.45%  |
| Samsung Electronics     | 289       | 12.36%  |
| Chimei Innolux          | 234       | 10%     |
| BOE                     | 192       | 8.21%   |
| Sharp                   | 109       | 4.66%   |
| Lenovo                  | 79        | 3.38%   |
| Apple                   | 72        | 3.08%   |
| Chi Mei Optoelectronics | 66        | 2.82%   |
| Dell                    | 64        | 2.74%   |
| Goldstar                | 57        | 2.44%   |
| PANDA                   | 31        | 1.33%   |
| LG Philips              | 29        | 1.24%   |
| Hewlett-Packard         | 29        | 1.24%   |
| Acer                    | 27        | 1.15%   |
| Ancor Communications    | 25        | 1.07%   |
| BenQ                    | 23        | 0.98%   |
| ASUSTek Computer        | 22        | 0.94%   |
| Toshiba                 | 18        | 0.77%   |
| ANX                     | 14        | 0.6%    |
| ViewSonic               | 13        | 0.56%   |
| InfoVision              | 12        | 0.51%   |
| Sony                    | 11        | 0.47%   |
| AOC                     | 10        | 0.43%   |
| Quanta Display          | 8         | 0.34%   |
| Panasonic               | 8         | 0.34%   |
| HannStar                | 8         | 0.34%   |
| Philips                 | 7         | 0.3%    |
| Seiko/Epson             | 6         | 0.26%   |
| CPT                     | 6         | 0.26%   |
| TMX                     | 5         | 0.21%   |
| LGD                     | 5         | 0.21%   |
| Insignia                | 5         | 0.21%   |
| IBM                     | 4         | 0.17%   |
| CSO                     | 4         | 0.17%   |
| Valve                   | 3         | 0.13%   |
| Unknown                 | 3         | 0.13%   |
| SANYO                   | 3         | 0.13%   |
| MSI                     | 3         | 0.13%   |
| NEC Computers           | 2         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 30        | 1.26%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 353x198mm 15.9-inch     | 29        | 1.22%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 17        | 0.71%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch            | 16        | 0.67%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 15        | 0.63%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 15        | 0.63%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 14        | 0.59%   |
| ANX ANX7530 U ANX7539 800x1280                                           | 14        | 0.59%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 12        | 0.5%    |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 12        | 0.5%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 12        | 0.5%    |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                  | 11        | 0.46%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 11        | 0.46%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 11        | 0.46%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                  | 10        | 0.42%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 10        | 0.42%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 10        | 0.42%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 10        | 0.42%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                 | 10        | 0.42%   |
| Toshiba TV TSB0206 1920x1080 886x498mm 40.0-inch                         | 9         | 0.38%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch             | 9         | 0.38%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 9         | 0.38%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 9         | 0.38%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 9         | 0.38%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 9         | 0.38%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch              | 8         | 0.34%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 8         | 0.34%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 8         | 0.34%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch    | 7         | 0.29%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch              | 7         | 0.29%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 7         | 0.29%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 7         | 0.29%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 7         | 0.29%   |
| BOE LCD Monitor BOE0718 1920x1080 309x173mm 13.9-inch                    | 7         | 0.29%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch            | 7         | 0.29%   |
| AU Optronics LCD Monitor AUO315C 1366x768 256x144mm 11.6-inch            | 7         | 0.29%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 7         | 0.29%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 7         | 0.29%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                     | 7         | 0.29%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                  | 6         | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 766       | 34.54%  |
| 1366x768 (WXGA)    | 698       | 31.47%  |
| 1600x900 (HD+)     | 140       | 6.31%   |
| 1280x800 (WXGA)    | 133       | 6%      |
| 3840x2160 (4K)     | 97        | 4.37%   |
| 2560x1440 (QHD)    | 56        | 2.52%   |
| 1440x900 (WXGA+)   | 52        | 2.34%   |
| 1680x1050 (WSXGA+) | 47        | 2.12%   |
| 1920x1200 (WUXGA)  | 42        | 1.89%   |
| 2880x1800          | 17        | 0.77%   |
| 1280x1024 (SXGA)   | 17        | 0.77%   |
| 800x1280           | 16        | 0.72%   |
| 3200x1800 (QHD+)   | 11        | 0.5%    |
| 1024x600           | 11        | 0.5%    |
| 3440x1440          | 10        | 0.45%   |
| 2560x1600          | 10        | 0.45%   |
| 3840x2400          | 9         | 0.41%   |
| 2560x1080          | 9         | 0.41%   |
| 1920x540           | 9         | 0.41%   |
| 1360x768           | 8         | 0.36%   |
| 1024x768 (XGA)     | 8         | 0.36%   |
| Unknown            | 7         | 0.32%   |
| 3456x2160          | 4         | 0.18%   |
| 3840x1080          | 3         | 0.14%   |
| 3200x2000          | 3         | 0.14%   |
| 2560x1700          | 3         | 0.14%   |
| 1680x945           | 3         | 0.14%   |
| 3840x1200          | 2         | 0.09%   |
| 3840x1100          | 2         | 0.09%   |
| 3072x1920          | 2         | 0.09%   |
| 3000x2000          | 2         | 0.09%   |
| 2288x1287          | 2         | 0.09%   |
| 2256x1504          | 2         | 0.09%   |
| 2160x1440          | 2         | 0.09%   |
| 1920x1280          | 2         | 0.09%   |
| 1600x1200          | 2         | 0.09%   |
| 1280x720 (HD)      | 2         | 0.09%   |
| 1024x576           | 2         | 0.09%   |
| 3520x1080          | 1         | 0.05%   |
| 3280x1080          | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1011      | 43.28%  |
| 13      | 303       | 12.97%  |
| 14      | 248       | 10.62%  |
| 17      | 168       | 7.19%   |
| 24      | 70        | 3%      |
| 27      | 69        | 2.95%   |
| Unknown | 62        | 2.65%   |
| 23      | 52        | 2.23%   |
| 12      | 45        | 1.93%   |
| 21      | 44        | 1.88%   |
| 11      | 35        | 1.5%    |
| 31      | 28        | 1.2%    |
| 22      | 22        | 0.94%   |
| 19      | 21        | 0.9%    |
| 34      | 20        | 0.86%   |
| 18      | 19        | 0.81%   |
| 20      | 13        | 0.56%   |
| 10      | 13        | 0.56%   |
| 74      | 9         | 0.39%   |
| 72      | 9         | 0.39%   |
| 84      | 8         | 0.34%   |
| 16      | 8         | 0.34%   |
| 54      | 7         | 0.3%    |
| 32      | 7         | 0.3%    |
| 25      | 6         | 0.26%   |
| 40      | 5         | 0.21%   |
| 37      | 5         | 0.21%   |
| 48      | 4         | 0.17%   |
| 26      | 4         | 0.17%   |
| 47      | 3         | 0.13%   |
| 43      | 3         | 0.13%   |
| 7       | 3         | 0.13%   |
| 42      | 2         | 0.09%   |
| 39      | 2         | 0.09%   |
| 28      | 2         | 0.09%   |
| 69      | 1         | 0.04%   |
| 57      | 1         | 0.04%   |
| 52      | 1         | 0.04%   |
| 49      | 1         | 0.04%   |
| 46      | 1         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 1362      | 58.88%  |
| 201-300     | 245       | 10.59%  |
| 351-400     | 227       | 9.81%   |
| 501-600     | 177       | 7.65%   |
| 401-500     | 108       | 4.67%   |
| Unknown     | 62        | 2.68%   |
| 601-700     | 39        | 1.69%   |
| 701-800     | 27        | 1.17%   |
| 1501-2000   | 27        | 1.17%   |
| 1001-1500   | 19        | 0.82%   |
| 801-900     | 12        | 0.52%   |
| 901-1000    | 4         | 0.17%   |
| 1-100       | 3         | 0.13%   |
| 101-200     | 1         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1609      | 78.56%  |
| 16/10   | 309       | 15.09%  |
| Unknown | 30        | 1.46%   |
| 3/2     | 22        | 1.07%   |
| 21/9    | 19        | 0.93%   |
| 5/4     | 18        | 0.88%   |
| 4/3     | 15        | 0.73%   |
| 0.62    | 14        | 0.68%   |
| 0.67    | 3         | 0.15%   |
| 6/5     | 2         | 0.1%    |
| 32/9    | 2         | 0.1%    |
| 3.40    | 2         | 0.1%    |
| 1.96    | 2         | 0.1%    |
| 3.20    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1007      | 43.35%  |
| 81-90          | 434       | 18.68%  |
| 201-250        | 152       | 6.54%   |
| 121-130        | 140       | 6.03%   |
| 71-80          | 110       | 4.74%   |
| 301-350        | 70        | 3.01%   |
| Unknown        | 62        | 2.67%   |
| 351-500        | 56        | 2.41%   |
| 151-200        | 46        | 1.98%   |
| 61-70          | 42        | 1.81%   |
| More than 1000 | 37        | 1.59%   |
| 51-60          | 37        | 1.59%   |
| 501-1000       | 25        | 1.08%   |
| 251-300        | 24        | 1.03%   |
| 141-150        | 24        | 1.03%   |
| 131-140        | 24        | 1.03%   |
| 41-50          | 13        | 0.56%   |
| 111-120        | 9         | 0.39%   |
| 91-100         | 7         | 0.3%    |
| 1-40           | 4         | 0.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 773       | 34.01%  |
| 121-160       | 750       | 33%     |
| 51-100        | 439       | 19.31%  |
| 161-240       | 119       | 5.24%   |
| More than 240 | 84        | 3.7%    |
| Unknown       | 62        | 2.73%   |
| 1-50          | 46        | 2.02%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1631      | 78.94%  |
| 2     | 338       | 16.36%  |
| 3     | 53        | 2.57%   |
| 0     | 43        | 2.08%   |
| 4     | 1         | 0.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1067      | 33.72%  |
| Realtek Semiconductor           | 932       | 29.46%  |
| Qualcomm Atheros                | 502       | 15.87%  |
| Broadcom                        | 253       | 8%      |
| Broadcom Limited                | 96        | 3.03%   |
| Marvell Technology Group        | 44        | 1.39%   |
| ASIX Electronics                | 29        | 0.92%   |
| TP-Link                         | 26        | 0.82%   |
| Ralink                          | 23        | 0.73%   |
| Nvidia                          | 22        | 0.7%    |
| MediaTek                        | 20        | 0.63%   |
| Linksys                         | 18        | 0.57%   |
| Ralink Technology               | 17        | 0.54%   |
| D-Link                          | 12        | 0.38%   |
| Lenovo                          | 10        | 0.32%   |
| DisplayLink                     | 9         | 0.28%   |
| ASUSTek Computer                | 9         | 0.28%   |
| Sierra Wireless                 | 8         | 0.25%   |
| Samsung Electronics             | 8         | 0.25%   |
| Qualcomm Atheros Communications | 7         | 0.22%   |
| Google                          | 5         | 0.16%   |
| AMD                             | 5         | 0.16%   |
| Qualcomm                        | 4         | 0.13%   |
| NetGear                         | 4         | 0.13%   |
| Research In Motion              | 3         | 0.09%   |
| JMicron Technology              | 3         | 0.09%   |
| D-Link System                   | 3         | 0.09%   |
| Apple                           | 3         | 0.09%   |
| Xiaomi                          | 2         | 0.06%   |
| Hewlett-Packard                 | 2         | 0.06%   |
| Edimax Technology               | 2         | 0.06%   |
| Aquantia                        | 2         | 0.06%   |
| U-Blox                          | 1         | 0.03%   |
| TRENDnet                        | 1         | 0.03%   |
| OnePlus Technology (Shenzhen)   | 1         | 0.03%   |
| Motorola PCS                    | 1         | 0.03%   |
| Microsoft                       | 1         | 0.03%   |
| Huawei Technologies             | 1         | 0.03%   |
| HTC (High Tech Computer)        | 1         | 0.03%   |
| HMD Global                      | 1         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 511       | 13.05%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 220       | 5.62%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 131       | 3.34%   |
| Intel Wireless 8265 / 8275                                        | 81        | 2.07%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 80        | 2.04%   |
| Intel Wi-Fi 6 AX200                                               | 80        | 2.04%   |
| Intel Wireless 7260                                               | 79        | 2.02%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 78        | 1.99%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 70        | 1.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 70        | 1.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 64        | 1.63%   |
| Intel Wireless 7265                                               | 63        | 1.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 56        | 1.43%   |
| Intel Wireless 8260                                               | 56        | 1.43%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 53        | 1.35%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 48        | 1.23%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 47        | 1.2%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 45        | 1.15%   |
| Intel 82577LM Gigabit Network Connection                          | 43        | 1.1%    |
| Intel Centrino Ultimate-N 6300                                    | 42        | 1.07%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 38        | 0.97%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 36        | 0.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 32        | 0.82%   |
| Intel Ethernet Connection I217-LM                                 | 32        | 0.82%   |
| Intel Wi-Fi 6 AX201                                               | 31        | 0.79%   |
| Intel Ethernet Connection I218-LM                                 | 31        | 0.79%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 27        | 0.69%   |
| ASIX AX88179 Gigabit Ethernet                                     | 27        | 0.69%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 26        | 0.66%   |
| Intel Ethernet Connection (4) I219-LM                             | 26        | 0.66%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 25        | 0.64%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 25        | 0.64%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 25        | 0.64%   |
| Intel Wireless 3165                                               | 25        | 0.64%   |
| Intel Centrino Wireless-N 2230                                    | 25        | 0.64%   |
| Intel Centrino Advanced-N 6200                                    | 25        | 0.64%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 24        | 0.61%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 23        | 0.59%   |
| Intel Centrino Advanced-N 6235                                    | 23        | 0.59%   |
| Intel 82567LM Gigabit Network Connection                          | 23        | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1011      | 47.91%  |
| Qualcomm Atheros                | 411       | 19.48%  |
| Realtek Semiconductor           | 278       | 13.18%  |
| Broadcom                        | 201       | 9.53%   |
| Broadcom Limited                | 58        | 2.75%   |
| TP-Link                         | 24        | 1.14%   |
| Ralink                          | 23        | 1.09%   |
| MediaTek                        | 20        | 0.95%   |
| Ralink Technology               | 17        | 0.81%   |
| Linksys                         | 16        | 0.76%   |
| D-Link                          | 11        | 0.52%   |
| ASUSTek Computer                | 9         | 0.43%   |
| Sierra Wireless                 | 8         | 0.38%   |
| Qualcomm Atheros Communications | 7         | 0.33%   |
| Qualcomm                        | 4         | 0.19%   |
| NetGear                         | 4         | 0.19%   |
| D-Link System                   | 3         | 0.14%   |
| Edimax Technology               | 2         | 0.09%   |
| TRENDnet                        | 1         | 0.05%   |
| Marvell Technology Group        | 1         | 0.05%   |
| Dell                            | 1         | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 81        | 3.81%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 80        | 3.76%   |
| Intel Wi-Fi 6 AX200                                                     | 80        | 3.76%   |
| Intel Wireless 7260                                                     | 79        | 3.72%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 78        | 3.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 70        | 3.29%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 64        | 3.01%   |
| Intel Wireless 7265                                                     | 63        | 2.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 56        | 2.63%   |
| Intel Wireless 8260                                                     | 56        | 2.63%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 53        | 2.49%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 48        | 2.26%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 47        | 2.21%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 45        | 2.12%   |
| Intel Centrino Ultimate-N 6300                                          | 42        | 1.98%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 38        | 1.79%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 36        | 1.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 32        | 1.51%   |
| Intel Wi-Fi 6 AX201                                                     | 31        | 1.46%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 27        | 1.27%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 26        | 1.22%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 25        | 1.18%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 25        | 1.18%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 25        | 1.18%   |
| Intel Wireless 3165                                                     | 25        | 1.18%   |
| Intel Centrino Wireless-N 2230                                          | 25        | 1.18%   |
| Intel Centrino Advanced-N 6200                                          | 25        | 1.18%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 24        | 1.13%   |
| Intel Centrino Advanced-N 6235                                          | 23        | 1.08%   |
| Realtek 802.11ac NIC                                                    | 22        | 1.03%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 22        | 1.03%   |
| Broadcom BCM43142 802.11b/g/n                                           | 22        | 1.03%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 21        | 0.99%   |
| Intel WiFi Link 5100                                                    | 21        | 0.99%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 21        | 0.99%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 20        | 0.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 20        | 0.94%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 20        | 0.94%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 19        | 0.89%   |
| Intel Wireless 3160                                                     | 17        | 0.8%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 823       | 46.97%  |
| Intel                    | 472       | 26.94%  |
| Qualcomm Atheros         | 154       | 8.79%   |
| Broadcom                 | 108       | 6.16%   |
| Marvell Technology Group | 43        | 2.45%   |
| Broadcom Limited         | 43        | 2.45%   |
| ASIX Electronics         | 29        | 1.66%   |
| Nvidia                   | 21        | 1.2%    |
| Lenovo                   | 10        | 0.57%   |
| DisplayLink              | 9         | 0.51%   |
| Samsung Electronics      | 8         | 0.46%   |
| Google                   | 5         | 0.29%   |
| TP-Link                  | 3         | 0.17%   |
| Research In Motion       | 3         | 0.17%   |
| JMicron Technology       | 3         | 0.17%   |
| Apple                    | 3         | 0.17%   |
| Xiaomi                   | 2         | 0.11%   |
| Linksys                  | 2         | 0.11%   |
| Hewlett-Packard          | 2         | 0.11%   |
| Aquantia                 | 2         | 0.11%   |
| Motorola PCS             | 1         | 0.06%   |
| Microsoft                | 1         | 0.06%   |
| Huawei Technologies      | 1         | 0.06%   |
| HTC (High Tech Computer) | 1         | 0.06%   |
| HMD Global               | 1         | 0.06%   |
| D-Link                   | 1         | 0.06%   |
| Attansic Technology      | 1         | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 511       | 28.82%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 220       | 12.41%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 131       | 7.39%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 70        | 3.95%   |
| Intel 82577LM Gigabit Network Connection                          | 43        | 2.43%   |
| Intel Ethernet Connection I217-LM                                 | 32        | 1.8%    |
| Intel Ethernet Connection I218-LM                                 | 31        | 1.75%   |
| ASIX AX88179 Gigabit Ethernet                                     | 27        | 1.52%   |
| Intel Ethernet Connection (4) I219-LM                             | 26        | 1.47%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 23        | 1.3%    |
| Intel 82567LM Gigabit Network Connection                          | 23        | 1.3%    |
| Intel Ethernet Connection I219-LM                                 | 22        | 1.24%   |
| Intel Ethernet Connection (4) I219-V                              | 20        | 1.13%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 20        | 1.13%   |
| Intel Ethernet Connection (3) I218-LM                             | 19        | 1.07%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 18        | 1.02%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 17        | 0.96%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 15        | 0.85%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 14        | 0.79%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 14        | 0.79%   |
| Intel Ethernet Connection I219-V                                  | 14        | 0.79%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 13        | 0.73%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 13        | 0.73%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 12        | 0.68%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 11        | 0.62%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 11        | 0.62%   |
| Nvidia MCP79 Ethernet                                             | 11        | 0.62%   |
| Intel Ethernet Connection (6) I219-V                              | 11        | 0.62%   |
| Intel 82579V Gigabit Network Connection                           | 11        | 0.62%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 11        | 0.62%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 11        | 0.62%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 9         | 0.51%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 9         | 0.51%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 9         | 0.51%   |
| Intel PRO/100 VE Network Connection                               | 8         | 0.45%   |
| Intel Ethernet Connection (7) I219-V                              | 8         | 0.45%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 8         | 0.45%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 7         | 0.39%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 7         | 0.39%   |
| Intel Ethernet Connection (2) I219-LM                             | 7         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1972      | 53.7%   |
| Ethernet | 1682      | 45.81%  |
| Modem    | 15        | 0.41%   |
| Unknown  | 3         | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1660      | 76.71%  |
| Ethernet | 504       | 23.29%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1548      | 76.79%  |
| 1     | 423       | 20.98%  |
| 0     | 28        | 1.39%   |
| 3     | 17        | 0.84%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1777      | 87.07%  |
| Yes  | 264       | 12.93%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 682       | 45.74%  |
| Broadcom                        | 129       | 8.65%   |
| Realtek Semiconductor           | 116       | 7.78%   |
| Qualcomm Atheros Communications | 110       | 7.38%   |
| Lite-On Technology              | 95        | 6.37%   |
| IMC Networks                    | 85        | 5.7%    |
| Apple                           | 67        | 4.49%   |
| Foxconn / Hon Hai               | 58        | 3.89%   |
| Dell                            | 35        | 2.35%   |
| Hewlett-Packard                 | 27        | 1.81%   |
| Cambridge Silicon Radio         | 26        | 1.74%   |
| ASUSTek Computer                | 13        | 0.87%   |
| Toshiba                         | 12        | 0.8%    |
| Ralink                          | 12        | 0.8%    |
| Alps Electric                   | 6         | 0.4%    |
| Realtek                         | 3         | 0.2%    |
| Logitech                        | 2         | 0.13%   |
| Dynex                           | 2         | 0.13%   |
| SINO WEALTH                     | 1         | 0.07%   |
| Ralink Technology               | 1         | 0.07%   |
| Qcom                            | 1         | 0.07%   |
| Primax Electronics              | 1         | 0.07%   |
| MediaTek                        | 1         | 0.07%   |
| Marvell Semiconductor           | 1         | 0.07%   |
| Kensington                      | 1         | 0.07%   |
| Fujitsu                         | 1         | 0.07%   |
| Foxconn International           | 1         | 0.07%   |
| D-Link System                   | 1         | 0.07%   |
| Askey Computer                  | 1         | 0.07%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 306       | 20.48%  |
| Intel AX201 Bluetooth                               | 107       | 7.16%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 84        | 5.62%   |
| Realtek Bluetooth Radio                             | 80        | 5.35%   |
| Intel AX200 Bluetooth                               | 78        | 5.22%   |
| Qualcomm Atheros  Bluetooth Device                  | 58        | 3.88%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 44        | 2.95%   |
| Apple Bluetooth Host Controller                     | 43        | 2.88%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 41        | 2.74%   |
| Foxconn / Hon Hai Bluetooth Device                  | 34        | 2.28%   |
| Lite-On Atheros AR3012 Bluetooth                    | 31        | 2.07%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 26        | 1.74%   |
| Realtek  Bluetooth 4.2 Adapter                      | 25        | 1.67%   |
| Broadcom BCM2045B (BDC-2.1)                         | 25        | 1.67%   |
| IMC Networks Bluetooth Radio                        | 22        | 1.47%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 20        | 1.34%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 19        | 1.27%   |
| IMC Networks 802.11ac WLAN Adapter                  | 16        | 1.07%   |
| Broadcom HP Portable SoftSailing                    | 16        | 1.07%   |
| Apple Bluetooth USB Host Controller                 | 16        | 1.07%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 15        | 1%      |
| Qualcomm Atheros AR3011 Bluetooth                   | 15        | 1%      |
| Intel Wireless-AC 3168 Bluetooth                    | 14        | 0.94%   |
| Intel AX210 Bluetooth                               | 14        | 0.94%   |
| HP Broadcom 2070 Bluetooth Combo                    | 14        | 0.94%   |
| Ralink RT3290 Bluetooth                             | 12        | 0.8%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 12        | 0.8%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 12        | 0.8%    |
| IMC Networks Wireless_Device                        | 11        | 0.74%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 10        | 0.67%   |
| IMC Networks Bluetooth Device                       | 10        | 0.67%   |
| Dell DW375 Bluetooth Module                         | 10        | 0.67%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 10        | 0.67%   |
| Lite-On Bluetooth Device                            | 9         | 0.6%    |
| Intel Bluetooth Device                              | 9         | 0.6%    |
| IMC Networks BCM20702A0                             | 9         | 0.6%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 9         | 0.6%    |
| Foxconn / Hon Hai BCM20702A0                        | 9         | 0.6%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 8         | 0.54%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 8         | 0.54%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1562      | 63.09%  |
| AMD                                  | 464       | 18.74%  |
| Nvidia                               | 290       | 11.71%  |
| C-Media Electronics                  | 18        | 0.73%   |
| Realtek Semiconductor                | 17        | 0.69%   |
| Logitech                             | 15        | 0.61%   |
| GN Netcom                            | 11        | 0.44%   |
| Lenovo                               | 10        | 0.4%    |
| Plantronics                          | 8         | 0.32%   |
| SteelSeries ApS                      | 6         | 0.24%   |
| JMTek                                | 6         | 0.24%   |
| Sony                                 | 4         | 0.16%   |
| Sennheiser Communications            | 4         | 0.16%   |
| Razer USA                            | 4         | 0.16%   |
| Blue Microphones                     | 4         | 0.16%   |
| No brand                             | 3         | 0.12%   |
| Kingston Technology                  | 3         | 0.12%   |
| Generalplus Technology               | 3         | 0.12%   |
| Creative Technology                  | 3         | 0.12%   |
| Texas Instruments                    | 2         | 0.08%   |
| Synaptics                            | 2         | 0.08%   |
| Native Instruments                   | 2         | 0.08%   |
| Focusrite-Novation                   | 2         | 0.08%   |
| Corsair                              | 2         | 0.08%   |
| Apple                                | 2         | 0.08%   |
| XMOS                                 | 1         | 0.04%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.04%   |
| Tenx Technology                      | 1         | 0.04%   |
| Shure                                | 1         | 0.04%   |
| Samson Technologies                  | 1         | 0.04%   |
| RODE Microphones                     | 1         | 0.04%   |
| RME                                  | 1         | 0.04%   |
| PreSonus Audio Electronics           | 1         | 0.04%   |
| Pioneer DJ                           | 1         | 0.04%   |
| Panasonic (Matsushita)               | 1         | 0.04%   |
| NAD Electronics                      | 1         | 0.04%   |
| Hewlett-Packard                      | 1         | 0.04%   |
| Harman                               | 1         | 0.04%   |
| GYROCOM C&C                          | 1         | 0.04%   |
| FiiO Electronics Technology          | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 200       | 6.63%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 196       | 6.49%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 147       | 4.87%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 131       | 4.34%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 131       | 4.34%   |
| AMD FCH Azalia Controller                                                                         | 115       | 3.81%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 104       | 3.45%   |
| Intel Cannon Lake PCH cAVS                                                                        | 96        | 3.18%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 83        | 2.75%   |
| Intel 8 Series HD Audio Controller                                                                | 83        | 2.75%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 72        | 2.39%   |
| AMD Kabini HDMI/DP Audio                                                                          | 72        | 2.39%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 69        | 2.29%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 66        | 2.19%   |
| Intel Broadwell-U Audio Controller                                                                | 64        | 2.12%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 63        | 2.09%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 62        | 2.05%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 61        | 2.02%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 56        | 1.86%   |
| Intel Comet Lake PCH cAVS                                                                         | 50        | 1.66%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 48        | 1.59%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 48        | 1.59%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 44        | 1.46%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 43        | 1.42%   |
| AMD High Definition Audio Controller                                                              | 39        | 1.29%   |
| AMD Trinity HDMI Audio Controller                                                                 | 36        | 1.19%   |
| Intel CM238 HD Audio Controller                                                                   | 32        | 1.06%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 31        | 1.03%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 30        | 0.99%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 29        | 0.96%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 28        | 0.93%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 25        | 0.83%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 24        | 0.8%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 24        | 0.8%    |
| Nvidia TU106 High Definition Audio Controller                                                     | 23        | 0.76%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 22        | 0.73%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 22        | 0.73%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 20        | 0.66%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 19        | 0.63%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 18        | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 326       | 27.74%  |
| SK hynix                                         | 295       | 25.11%  |
| Micron Technology                                | 140       | 11.91%  |
| Kingston                                         | 97        | 8.26%   |
| Unknown                                          | 95        | 8.09%   |
| Crucial                                          | 51        | 4.34%   |
| Elpida                                           | 29        | 2.47%   |
| Nanya Technology                                 | 23        | 1.96%   |
| Ramaxel Technology                               | 22        | 1.87%   |
| G.Skill                                          | 22        | 1.87%   |
| Corsair                                          | 16        | 1.36%   |
| A-DATA Technology                                | 15        | 1.28%   |
| Patriot                                          | 7         | 0.6%    |
| Toshiba                                          | 5         | 0.43%   |
| Unknown (ABCD)                                   | 3         | 0.26%   |
| PNY                                              | 3         | 0.26%   |
| ASint Technology                                 | 3         | 0.26%   |
| SHARETRONIC                                      | 2         | 0.17%   |
| Neo Forza                                        | 2         | 0.17%   |
| Axiom                                            | 2         | 0.17%   |
| Unknown                                          | 2         | 0.17%   |
| Unknown (7F7F7F94FFFFFFFF)                       | 1         | 0.09%   |
| Unknown (0x505344323247363637325300000000000000) | 1         | 0.09%   |
| Unknown (0x4D342037305432383634515A332D43453620) | 1         | 0.09%   |
| Unknown (0x0C26)                                 | 1         | 0.09%   |
| Unknown (08AE)                                   | 1         | 0.09%   |
| Transcend                                        | 1         | 0.09%   |
| Timetec                                          | 1         | 0.09%   |
| Qimonda                                          | 1         | 0.09%   |
| OM Nanotech                                      | 1         | 0.09%   |
| Lexar                                            | 1         | 0.09%   |
| KingFast                                         | 1         | 0.09%   |
| Goldkey                                          | 1         | 0.09%   |
| fef5                                             | 1         | 0.09%   |
| CSX                                              | 1         | 0.09%   |
| Avant                                            | 1         | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 19        | 1.52%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 17        | 1.36%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 15        | 1.2%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 14        | 1.12%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 14        | 1.12%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 14        | 1.12%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 14        | 1.12%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 13        | 1.04%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 13        | 1.04%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 12        | 0.96%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 12        | 0.96%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 12        | 0.96%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 11        | 0.88%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 10        | 0.8%    |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 10        | 0.8%    |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 9         | 0.72%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 9         | 0.72%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 9         | 0.72%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 9         | 0.72%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 9         | 0.72%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 9         | 0.72%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 8         | 0.64%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 8         | 0.64%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 8         | 0.64%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 0.64%   |
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 8400MT/s        | 8         | 0.64%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 8         | 0.64%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 7         | 0.56%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 7         | 0.56%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 7         | 0.56%   |
| Samsung RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s           | 7         | 0.56%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 7         | 0.56%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 7         | 0.56%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 7         | 0.56%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 7         | 0.56%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2667MT/s                   | 6         | 0.48%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.48%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 6         | 0.48%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.48%   |
| SK hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 6         | 0.48%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 411       | 41.94%  |
| DDR3    | 383       | 39.08%  |
| DDR2    | 51        | 5.2%    |
| LPDDR3  | 46        | 4.69%   |
| LPDDR4  | 41        | 4.18%   |
| SDRAM   | 22        | 2.24%   |
| Unknown | 14        | 1.43%   |
| DDR5    | 5         | 0.51%   |
| DDR     | 5         | 0.51%   |
| LPDDR5  | 1         | 0.1%    |
| DRAM    | 1         | 0.1%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 873       | 89.45%  |
| Row Of Chips | 79        | 8.09%   |
| Chip         | 13        | 1.33%   |
| Unknown      | 8         | 0.82%   |
| DIMM         | 3         | 0.31%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 397       | 36.32%  |
| 4096  | 372       | 34.03%  |
| 2048  | 141       | 12.9%   |
| 16384 | 131       | 11.99%  |
| 1024  | 36        | 3.29%   |
| 32768 | 14        | 1.28%   |
| 512   | 1         | 0.09%   |
| 256   | 1         | 0.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 260       | 24.19%  |
| 2667    | 206       | 19.16%  |
| 3200    | 149       | 13.86%  |
| 2400    | 83        | 7.72%   |
| 2133    | 67        | 6.23%   |
| 1334    | 58        | 5.4%    |
| 1333    | 48        | 4.47%   |
| 667     | 28        | 2.6%    |
| 1067    | 26        | 2.42%   |
| 4267    | 19        | 1.77%   |
| Unknown | 18        | 1.67%   |
| 1867    | 17        | 1.58%   |
| 4199    | 13        | 1.21%   |
| 3266    | 12        | 1.12%   |
| 800     | 12        | 1.12%   |
| 1066    | 11        | 1.02%   |
| 8400    | 8         | 0.74%   |
| 4800    | 7         | 0.65%   |
| 975     | 7         | 0.65%   |
| 533     | 6         | 0.56%   |
| 3733    | 4         | 0.37%   |
| 4266    | 3         | 0.28%   |
| 2048    | 3         | 0.28%   |
| 6400    | 2         | 0.19%   |
| 1639    | 2         | 0.19%   |
| 2666    | 1         | 0.09%   |
| 1866    | 1         | 0.09%   |
| 1200    | 1         | 0.09%   |
| 933     | 1         | 0.09%   |
| 400     | 1         | 0.09%   |
| 333     | 1         | 0.09%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 7         | 31.82%  |
| Brother Industries  | 7         | 31.82%  |
| Samsung Electronics | 5         | 22.73%  |
| Canon               | 2         | 9.09%   |
| Prolific Technology | 1         | 4.55%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Samsung M2070 Series                            | 2         | 8.7%    |
| HP OfficeJet 3830 series                        | 2         | 8.7%    |
| Canon PIXMA MG2900 Series                       | 2         | 8.7%    |
| Samsung ML-2510 Series                          | 1         | 4.35%   |
| Samsung M262x/M282x Xpress Series Laser Printer | 1         | 4.35%   |
| Samsung M2020 Series                            | 1         | 4.35%   |
| Prolific PL2305 Parallel Port                   | 1         | 4.35%   |
| HP LaserJet Professional P1102w                 | 1         | 4.35%   |
| HP LaserJet 1160 series                         | 1         | 4.35%   |
| HP LaserJet 1018                                | 1         | 4.35%   |
| HP ENVY 5000 series                             | 1         | 4.35%   |
| HP ENVY 4520 series                             | 1         | 4.35%   |
| Brother Printer                                 | 1         | 4.35%   |
| Brother MFC-L2730DW series                      | 1         | 4.35%   |
| Brother MFC-J6945DW                             | 1         | 4.35%   |
| Brother MFC-9330CDW                             | 1         | 4.35%   |
| Brother HL-L2390DW                              | 1         | 4.35%   |
| Brother HL-2270DW Laser Printer                 | 1         | 4.35%   |
| Brother HL-2170W series                         | 1         | 4.35%   |
| Brother DCP-L2550DW series                      | 1         | 4.35%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 4         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                    | Notebooks | Percent |
|--------------------------|-----------|---------|
| Canon CanoScan LiDE 220  | 2         | 50%     |
| Canon CanoScan LiDE 700F | 1         | 25%     |
| Canon CanoScan 4200F     | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 418       | 24.27%  |
| Microdia                               | 192       | 11.15%  |
| IMC Networks                           | 167       | 9.7%    |
| Acer                                   | 142       | 8.25%   |
| Realtek Semiconductor                  | 136       | 7.9%    |
| Sunplus Innovation Technology          | 112       | 6.5%    |
| Suyin                                  | 79        | 4.59%   |
| Quanta                                 | 76        | 4.41%   |
| Apple                                  | 63        | 3.66%   |
| Cheng Uei Precision Industry (Foxlink) | 46        | 2.67%   |
| Lite-On Technology                     | 32        | 1.86%   |
| Logitech                               | 30        | 1.74%   |
| Ricoh                                  | 26        | 1.51%   |
| Syntek                                 | 25        | 1.45%   |
| Silicon Motion                         | 24        | 1.39%   |
| Lenovo                                 | 23        | 1.34%   |
| Luxvisions Innotech Limited            | 19        | 1.1%    |
| Importek                               | 18        | 1.05%   |
| Samsung Electronics                    | 14        | 0.81%   |
| Alcor Micro                            | 14        | 0.81%   |
| Microsoft                              | 9         | 0.52%   |
| ALi                                    | 9         | 0.52%   |
| Primax Electronics                     | 7         | 0.41%   |
| OmniVision Technologies                | 7         | 0.41%   |
| Z-Star Microelectronics                | 4         | 0.23%   |
| Sonix Technology                       | 3         | 0.17%   |
| LG Electronics                         | 3         | 0.17%   |
| MacroSilicon                           | 2         | 0.12%   |
| Genesys Logic                          | 2         | 0.12%   |
| AVerMedia Technologies                 | 2         | 0.12%   |
| YGTek                                  | 1         | 0.06%   |
| WaveRider Communications               | 1         | 0.06%   |
| Unknown                                | 1         | 0.06%   |
| Sunplus Technology                     | 1         | 0.06%   |
| Sony                                   | 1         | 0.06%   |
| Razer USA                              | 1         | 0.06%   |
| Nikon                                  | 1         | 0.06%   |
| LG Innotek                             | 1         | 0.06%   |
| Jieli Technology                       | 1         | 0.06%   |
| Intel                                  | 1         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 88        | 5.08%   |
| Microdia Integrated_Webcam_HD                       | 87        | 5.02%   |
| Realtek Integrated_Webcam_HD                        | 57        | 3.29%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 54        | 3.12%   |
| Chicony HD WebCam                                   | 42        | 2.42%   |
| IMC Networks Integrated Camera                      | 37        | 2.14%   |
| Acer Integrated Camera                              | 34        | 1.96%   |
| Microdia Integrated Webcam                          | 27        | 1.56%   |
| Sunplus Integrated_Webcam_HD                        | 24        | 1.38%   |
| Sunplus HD WebCam                                   | 21        | 1.21%   |
| Chicony VGA WebCam                                  | 20        | 1.15%   |
| Apple Built-in iSight                               | 20        | 1.15%   |
| Apple iPhone5/5C/5S/6                               | 19        | 1.1%    |
| Acer Lenovo EasyCamera                              | 19        | 1.1%    |
| Lite-On Integrated Camera                           | 18        | 1.04%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 18        | 1.04%   |
| Syntek Integrated Camera                            | 17        | 0.98%   |
| Apple FaceTime HD Camera                            | 17        | 0.98%   |
| Chicony USB 2.0 Camera                              | 16        | 0.92%   |
| Quanta VGA WebCam                                   | 15        | 0.87%   |
| Quanta HP TrueVision HD Camera                      | 15        | 0.87%   |
| Chicony USB2.0 HD UVC WebCam                        | 15        | 0.87%   |
| Chicony HP Truevision HD                            | 15        | 0.87%   |
| Acer HD Webcam                                      | 15        | 0.87%   |
| Samsung Galaxy A5 (MTP)                             | 14        | 0.81%   |
| Quanta HD User Facing                               | 14        | 0.81%   |
| Realtek USB Camera                                  | 13        | 0.75%   |
| Chicony TOSHIBA Web Camera - HD                     | 13        | 0.75%   |
| Acer SunplusIT Integrated Camera                    | 13        | 0.75%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 12        | 0.69%   |
| Sunplus HP HD Webcam [Fixed]                        | 11        | 0.63%   |
| Quanta HP Webcam                                    | 11        | 0.63%   |
| Chicony USB2.0 VGA UVC WebCam                       | 11        | 0.63%   |
| Chicony HP HD Camera                                | 11        | 0.63%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 11        | 0.63%   |
| Realtek Acer 640 x 480 laptop camera                | 10        | 0.58%   |
| Quanta HD Webcam                                    | 10        | 0.58%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 10        | 0.58%   |
| Lenovo Integrated Webcam [R5U877]                   | 10        | 0.58%   |
| IMC Networks HP TrueVision HD Camera                | 10        | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 155       | 40.47%  |
| Synaptics                  | 78        | 20.37%  |
| Shenzhen Goodix Technology | 35        | 9.14%   |
| Upek                       | 30        | 7.83%   |
| AuthenTec                  | 27        | 7.05%   |
| Elan Microelectronics      | 22        | 5.74%   |
| LighTuning Technology      | 18        | 4.7%    |
| STMicroelectronics         | 14        | 3.66%   |
| Microsoft                  | 1         | 0.26%   |
| HOLTEK                     | 1         | 0.26%   |
| Focal-systems.Corp         | 1         | 0.26%   |
| Dell                       | 1         | 0.26%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 39        | 10.18%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 29        | 7.57%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 28        | 7.31%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 27        | 7.05%   |
| Shenzhen Goodix FingerPrint                                                | 22        | 5.74%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 21        | 5.48%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 17        | 4.44%   |
| Validity Sensors VFS491                                                    | 17        | 4.44%   |
| Elan ELAN:Fingerprint                                                      | 17        | 4.44%   |
| Validity Sensors Synaptics WBDI                                            | 14        | 3.66%   |
| STMicroelectronics Fingerprint Reader                                      | 14        | 3.66%   |
| AuthenTec AES2810                                                          | 13        | 3.39%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 11        | 2.87%   |
| Shenzhen Goodix  FingerPrint Device                                        | 10        | 2.61%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 10        | 2.61%   |
| Unknown                                                                    | 10        | 2.61%   |
| Validity Sensors Fingerprint scanner                                       | 8         | 2.09%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 7         | 1.83%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 7         | 1.83%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 1.57%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 6         | 1.57%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 5         | 1.31%   |
| Elan ELAN:ARM-M4                                                           | 5         | 1.31%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 1.04%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 1.04%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 0.78%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 0.78%   |
| AuthenTec AES1600                                                          | 3         | 0.78%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 2         | 0.52%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 0.52%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.52%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 0.52%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 2         | 0.52%   |
| Synaptics  WBDI                                                            | 2         | 0.52%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 0.52%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.26%   |
| Synaptics WBDI Device                                                      | 1         | 0.26%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.26%   |
| Microsoft Fingerprint Reader                                               | 1         | 0.26%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.26%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 69        | 43.4%   |
| Alcor Micro               | 31        | 19.5%   |
| Upek                      | 21        | 13.21%  |
| O2 Micro                  | 21        | 13.21%  |
| Lenovo                    | 11        | 6.92%   |
| Gemalto (was Gemplus)     | 3         | 1.89%   |
| Yubico.com                | 1         | 0.63%   |
| Giesecke & Devrient       | 1         | 0.63%   |
| Aladdin Knowledge Systems | 1         | 0.63%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 39        | 24.53%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 30        | 18.87%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 21        | 13.21%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 18        | 11.32%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 16        | 10.06%  |
| Lenovo Integrated Smart Card Reader                                          | 11        | 6.92%   |
| Broadcom 5880                                                                | 8         | 5.03%   |
| Broadcom 58200                                                               | 5         | 3.14%   |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 1.89%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 3         | 1.89%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.63%   |
| Giesecke & Devrient StarSign CUT S                                           | 1         | 0.63%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.63%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.63%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.63%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1303      | 63.22%  |
| 1     | 601       | 29.16%  |
| 2     | 131       | 6.36%   |
| 3     | 19        | 0.92%   |
| 4     | 5         | 0.24%   |
| 6     | 1         | 0.05%   |
| 5     | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 376       | 41.09%  |
| Chipcard                 | 147       | 16.07%  |
| Graphics card            | 140       | 15.3%   |
| Net/wireless             | 85        | 9.29%   |
| Multimedia controller    | 46        | 5.03%   |
| Storage                  | 28        | 3.06%   |
| Bluetooth                | 20        | 2.19%   |
| Communication controller | 16        | 1.75%   |
| Camera                   | 15        | 1.64%   |
| Net/ethernet             | 10        | 1.09%   |
| Modem                    | 8         | 0.87%   |
| Card reader              | 6         | 0.66%   |
| Sound                    | 5         | 0.55%   |
| Network                  | 4         | 0.44%   |
| Flash memory             | 4         | 0.44%   |
| Storage/ide              | 2         | 0.22%   |
| Unclassified device      | 1         | 0.11%   |
| Tv card                  | 1         | 0.11%   |
| Firewire controller      | 1         | 0.11%   |

