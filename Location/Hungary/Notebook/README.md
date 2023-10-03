Linux in Hungary - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Hungary.

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

Total: 4612

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | ProBook 640 G8 Notebook ... | [4567599161](https://linux-hardware.org/?probe=4567599161) | Sep 29, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [526458167b](https://linux-hardware.org/?probe=526458167b) | Sep 29, 2023 |
| Dell          | Inspiron 3542               | [b7faf1054b](https://linux-hardware.org/?probe=b7faf1054b) | Sep 29, 2023 |
| Acer          | Swift SF114-34              | [9d618e345a](https://linux-hardware.org/?probe=9d618e345a) | Sep 29, 2023 |
| Dell          | Inspiron 5559               | [ea6622fcde](https://linux-hardware.org/?probe=ea6622fcde) | Sep 28, 2023 |
| Dell          | Inspiron 5559               | [a7e3c38a52](https://linux-hardware.org/?probe=a7e3c38a52) | Sep 28, 2023 |
| eMachines     | E725                        | [2c76723d59](https://linux-hardware.org/?probe=2c76723d59) | Sep 28, 2023 |
| Zebra Tech... | 10-WLAN-1                   | [9959efdb76](https://linux-hardware.org/?probe=9959efdb76) | Sep 27, 2023 |
| HP            | 250 G1                      | [0ec87fea6c](https://linux-hardware.org/?probe=0ec87fea6c) | Sep 27, 2023 |
| Dell          | Inspiron 5558               | [e8577ce363](https://linux-hardware.org/?probe=e8577ce363) | Sep 27, 2023 |
| ASUSTek       | X550LN                      | [390c16a341](https://linux-hardware.org/?probe=390c16a341) | Sep 26, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | [6b0a58d94c](https://linux-hardware.org/?probe=6b0a58d94c) | Sep 25, 2023 |
| HP            | 250 G1                      | [1aa0ca441a](https://linux-hardware.org/?probe=1aa0ca441a) | Sep 25, 2023 |
| ASUSTek       | X550CL                      | [9a2c66690c](https://linux-hardware.org/?probe=9a2c66690c) | Sep 25, 2023 |
| Apple         | MacBookAir5,2               | [137fbb8afb](https://linux-hardware.org/?probe=137fbb8afb) | Sep 25, 2023 |
| Fujitsu       | LIFEBOOK A530               | [dc76c26d4e](https://linux-hardware.org/?probe=dc76c26d4e) | Sep 24, 2023 |
| ASUSTek       | G750JX                      | [dc6cea804c](https://linux-hardware.org/?probe=dc6cea804c) | Sep 24, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [fcdc931f2b](https://linux-hardware.org/?probe=fcdc931f2b) | Sep 24, 2023 |
| Toshiba       | Satellite C55-A-1NV         | [2d441ed803](https://linux-hardware.org/?probe=2d441ed803) | Sep 24, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [0c9651a144](https://linux-hardware.org/?probe=0c9651a144) | Sep 24, 2023 |
| HP            | Notebook                    | [b222ca41de](https://linux-hardware.org/?probe=b222ca41de) | Sep 24, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | [b4a2e6cb0a](https://linux-hardware.org/?probe=b4a2e6cb0a) | Sep 24, 2023 |
| Dell          | Inspiron 5558               | [22a7b0cc9c](https://linux-hardware.org/?probe=22a7b0cc9c) | Sep 24, 2023 |
| Lenovo        | ThinkPad T410 2537VFQ       | [8d4bdbafa8](https://linux-hardware.org/?probe=8d4bdbafa8) | Sep 23, 2023 |
| Lenovo        | Y50-70 20378                | [d967e2d2a3](https://linux-hardware.org/?probe=d967e2d2a3) | Sep 23, 2023 |
| Lenovo        | Y50-70 20378                | [477998353b](https://linux-hardware.org/?probe=477998353b) | Sep 23, 2023 |
| HP            | Compaq 6710b (KE121EA#AK... | [a5b9ab6a07](https://linux-hardware.org/?probe=a5b9ab6a07) | Sep 23, 2023 |
| HP            | 650                         | [3c45902b7c](https://linux-hardware.org/?probe=3c45902b7c) | Sep 23, 2023 |
| Lenovo        | IdeaPad Slim 3 15AMN8 82... | [c933242918](https://linux-hardware.org/?probe=c933242918) | Sep 22, 2023 |
| Dell          | Latitude 7390               | [1aab1b313f](https://linux-hardware.org/?probe=1aab1b313f) | Sep 22, 2023 |
| HP            | 250 G1                      | [44dde35a76](https://linux-hardware.org/?probe=44dde35a76) | Sep 22, 2023 |
| Dell          | Latitude E5520              | [ae034f7a6b](https://linux-hardware.org/?probe=ae034f7a6b) | Sep 22, 2023 |
| HP            | Laptop 15-dw1xxx            | [18581b1af5](https://linux-hardware.org/?probe=18581b1af5) | Sep 22, 2023 |
| Acer          | Aspire E5-575G              | [bb5eff384a](https://linux-hardware.org/?probe=bb5eff384a) | Sep 22, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [942f5325d2](https://linux-hardware.org/?probe=942f5325d2) | Sep 22, 2023 |
| Lenovo        | ThinkPad X250 20CLS1JN00    | [c71bb49dcd](https://linux-hardware.org/?probe=c71bb49dcd) | Sep 21, 2023 |
| Dell          | Inspiron 5567               | [25e14aaf2b](https://linux-hardware.org/?probe=25e14aaf2b) | Sep 21, 2023 |
| Dell          | Latitude E7240              | [3e8e36e3ea](https://linux-hardware.org/?probe=3e8e36e3ea) | Sep 21, 2023 |
| ASUSTek       | K54HR                       | [8552d31b3c](https://linux-hardware.org/?probe=8552d31b3c) | Sep 21, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [32e2046699](https://linux-hardware.org/?probe=32e2046699) | Sep 21, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [22733fb7ba](https://linux-hardware.org/?probe=22733fb7ba) | Sep 21, 2023 |
| Dell          | Inspiron 3576               | [a76faead17](https://linux-hardware.org/?probe=a76faead17) | Sep 21, 2023 |
| Dell          | Latitude E6220              | [dd26ec3c45](https://linux-hardware.org/?probe=dd26ec3c45) | Sep 21, 2023 |
| Dell          | Inspiron 15-3567            | [cff5fbdefd](https://linux-hardware.org/?probe=cff5fbdefd) | Sep 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [9f1f1562ed](https://linux-hardware.org/?probe=9f1f1562ed) | Sep 21, 2023 |
| Fujitsu Si... | AMILO Li3910                | [14714d058e](https://linux-hardware.org/?probe=14714d058e) | Sep 19, 2023 |
| Dell          | Latitude E6430              | [d83d7bbfa8](https://linux-hardware.org/?probe=d83d7bbfa8) | Sep 18, 2023 |
| Acer          | Aspire A315-59              | [d00d3fed03](https://linux-hardware.org/?probe=d00d3fed03) | Sep 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [3bb8e84b6b](https://linux-hardware.org/?probe=3bb8e84b6b) | Sep 17, 2023 |
| Jumper        | EZbook                      | [bd0a13e867](https://linux-hardware.org/?probe=bd0a13e867) | Sep 16, 2023 |
| Dell          | Latitude E6220              | [8a341bd0e2](https://linux-hardware.org/?probe=8a341bd0e2) | Sep 16, 2023 |
| HP            | 650                         | [f648ca59f3](https://linux-hardware.org/?probe=f648ca59f3) | Sep 16, 2023 |
| Lenovo        | ThinkPad T450 20BVA01QHV    | [4f0a2bdfdc](https://linux-hardware.org/?probe=4f0a2bdfdc) | Sep 15, 2023 |
| Apple         | MacBookPro16,2              | [601a3eed6e](https://linux-hardware.org/?probe=601a3eed6e) | Sep 15, 2023 |
| Acer          | Swift SF314-43              | [ae2f1fa903](https://linux-hardware.org/?probe=ae2f1fa903) | Sep 15, 2023 |
| Dell          | Latitude 7390               | [c2529c08a4](https://linux-hardware.org/?probe=c2529c08a4) | Sep 14, 2023 |
| Dell          | Inspiron 3593               | [04d9ccd10f](https://linux-hardware.org/?probe=04d9ccd10f) | Sep 14, 2023 |
| HP            | 250 G1                      | [05483d5695](https://linux-hardware.org/?probe=05483d5695) | Sep 14, 2023 |
| Insyde        | Braswell                    | [1fb0864056](https://linux-hardware.org/?probe=1fb0864056) | Sep 14, 2023 |
| Lenovo        | IdeaPad Slim 3 15AMN8 82... | [fcac50bfba](https://linux-hardware.org/?probe=fcac50bfba) | Sep 13, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [8dba4d978a](https://linux-hardware.org/?probe=8dba4d978a) | Sep 13, 2023 |
| Dell          | Latitude E6430              | [79cf77c6ba](https://linux-hardware.org/?probe=79cf77c6ba) | Sep 12, 2023 |
| Dell          | Latitude E6220              | [f34fd65819](https://linux-hardware.org/?probe=f34fd65819) | Sep 12, 2023 |
| Dell          | Inspiron 5558               | [ec4efd4d4d](https://linux-hardware.org/?probe=ec4efd4d4d) | Sep 11, 2023 |
| HP            | 245 14 inch G9 Notebook ... | [e72c31a6fc](https://linux-hardware.org/?probe=e72c31a6fc) | Sep 11, 2023 |
| Dell          | Inspiron 15-3567            | [933a72acff](https://linux-hardware.org/?probe=933a72acff) | Sep 10, 2023 |
| HP            | Notebook                    | [231eb17318](https://linux-hardware.org/?probe=231eb17318) | Sep 10, 2023 |
| Lenovo        | Yoga S740-14IIL 81RS        | [5fc8984800](https://linux-hardware.org/?probe=5fc8984800) | Sep 10, 2023 |
| Dell          | Vostro 1015                 | [06e4b83617](https://linux-hardware.org/?probe=06e4b83617) | Sep 09, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [0f8249e50f](https://linux-hardware.org/?probe=0f8249e50f) | Sep 09, 2023 |
| Lenovo        | ThinkPad X395 20NMS0YG00    | [b3697e5a7e](https://linux-hardware.org/?probe=b3697e5a7e) | Sep 09, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [7f678086c3](https://linux-hardware.org/?probe=7f678086c3) | Sep 08, 2023 |
| Toshiba       | Satellite C55-A-1NV         | [d0f37c70e7](https://linux-hardware.org/?probe=d0f37c70e7) | Sep 08, 2023 |
| Dell          | Vostro 1015                 | [9c672d2801](https://linux-hardware.org/?probe=9c672d2801) | Sep 07, 2023 |
| Dell          | Latitude E6540              | [2832b1dd0d](https://linux-hardware.org/?probe=2832b1dd0d) | Sep 06, 2023 |
| ASUSTek       | X200MA                      | [e5a99beac7](https://linux-hardware.org/?probe=e5a99beac7) | Sep 06, 2023 |
| Dell          | Latitude 7490               | [2a945e76de](https://linux-hardware.org/?probe=2a945e76de) | Sep 05, 2023 |
| Lenovo        | G570 4334                   | [ce571e2d16](https://linux-hardware.org/?probe=ce571e2d16) | Sep 05, 2023 |
| Dell          | Latitude 7390               | [4d913a8444](https://linux-hardware.org/?probe=4d913a8444) | Sep 05, 2023 |
| Acer          | TravelMate P215-41-G2       | [6a1b31cf59](https://linux-hardware.org/?probe=6a1b31cf59) | Sep 05, 2023 |
| Dell          | Inspiron 5379               | [cafe064514](https://linux-hardware.org/?probe=cafe064514) | Sep 05, 2023 |
| Lenovo        | ThinkPad T520 4243WCR       | [181ef642cd](https://linux-hardware.org/?probe=181ef642cd) | Sep 05, 2023 |
| Dell          | Inspiron 15-3567            | [2fe06014b3](https://linux-hardware.org/?probe=2fe06014b3) | Sep 05, 2023 |
| Dell          | Latitude 7390               | [2c6e7f955b](https://linux-hardware.org/?probe=2c6e7f955b) | Sep 05, 2023 |
| HP            | Notebook                    | [76a4d54b3b](https://linux-hardware.org/?probe=76a4d54b3b) | Sep 04, 2023 |
| Dell          | Latitude 7390               | [cdee70b142](https://linux-hardware.org/?probe=cdee70b142) | Sep 04, 2023 |
| HP            | Laptop 15-dw1xxx            | [435d20add8](https://linux-hardware.org/?probe=435d20add8) | Sep 04, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [daeb81e2f6](https://linux-hardware.org/?probe=daeb81e2f6) | Sep 04, 2023 |
| eMachines     | E725                        | [cb1c5bd673](https://linux-hardware.org/?probe=cb1c5bd673) | Sep 03, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [90fb74ac63](https://linux-hardware.org/?probe=90fb74ac63) | Sep 03, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [3e196c9509](https://linux-hardware.org/?probe=3e196c9509) | Sep 03, 2023 |
| Packard Be... | EasyNote TJ65               | [55bb236bde](https://linux-hardware.org/?probe=55bb236bde) | Sep 03, 2023 |
| Lenovo        | ThinkPad T480 20L6S2KV20    | [248ef69016](https://linux-hardware.org/?probe=248ef69016) | Sep 03, 2023 |
| Dell          | Inspiron 5558               | [87cb36af8d](https://linux-hardware.org/?probe=87cb36af8d) | Sep 03, 2023 |
| Lenovo        | G565 20071                  | [289dd0308b](https://linux-hardware.org/?probe=289dd0308b) | Sep 02, 2023 |
| HP            | 255 G2                      | [27b48aa011](https://linux-hardware.org/?probe=27b48aa011) | Sep 02, 2023 |
| Acer          | Aspire 5715Z                | [22c3bee6fa](https://linux-hardware.org/?probe=22c3bee6fa) | Sep 02, 2023 |
| Dell          | Inspiron 7737               | [c1ad093dbb](https://linux-hardware.org/?probe=c1ad093dbb) | Sep 02, 2023 |
| Dell          | Inspiron 5379               | [1cbc463a43](https://linux-hardware.org/?probe=1cbc463a43) | Sep 02, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [5e95785b8e](https://linux-hardware.org/?probe=5e95785b8e) | Sep 01, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c37cbe9bd9](https://linux-hardware.org/?probe=c37cbe9bd9) | Sep 01, 2023 |
| ASUSTek       | X550CL                      | [e1eb9c4b56](https://linux-hardware.org/?probe=e1eb9c4b56) | Sep 01, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [458b3b6310](https://linux-hardware.org/?probe=458b3b6310) | Aug 31, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [4d1e47297b](https://linux-hardware.org/?probe=4d1e47297b) | Aug 30, 2023 |
| ASUSTek       | K52JB                       | [ddcb97361b](https://linux-hardware.org/?probe=ddcb97361b) | Aug 30, 2023 |
| Dell          | Inspiron 5567               | [0eddf6dfcd](https://linux-hardware.org/?probe=0eddf6dfcd) | Aug 30, 2023 |
| Dell          | Latitude E7240              | [ba4d78320f](https://linux-hardware.org/?probe=ba4d78320f) | Aug 30, 2023 |
| Apple         | MacBookAir5,2               | [8e595f3214](https://linux-hardware.org/?probe=8e595f3214) | Aug 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [41797b2df4](https://linux-hardware.org/?probe=41797b2df4) | Aug 30, 2023 |
| HP            | 250 G1                      | [6821396f96](https://linux-hardware.org/?probe=6821396f96) | Aug 29, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [0f7047f2c2](https://linux-hardware.org/?probe=0f7047f2c2) | Aug 29, 2023 |
| Acer          | Aspire E5-575G              | [9c733aac9d](https://linux-hardware.org/?probe=9c733aac9d) | Aug 28, 2023 |
| GPD           | G1619-01                    | [0e12028a4d](https://linux-hardware.org/?probe=0e12028a4d) | Aug 28, 2023 |
| Apple         | MacBookAir5,2               | [635743c7d4](https://linux-hardware.org/?probe=635743c7d4) | Aug 28, 2023 |
| Lenovo        | ThinkPad X220 4291C84       | [623b0f76d1](https://linux-hardware.org/?probe=623b0f76d1) | Aug 28, 2023 |
| Lenovo        | ThinkPad X250 20CLS1JN00    | [cb57dd666e](https://linux-hardware.org/?probe=cb57dd666e) | Aug 28, 2023 |
| eMachines     | E725                        | [415b4166b9](https://linux-hardware.org/?probe=415b4166b9) | Aug 27, 2023 |
| eMachines     | E725                        | [edb02e1501](https://linux-hardware.org/?probe=edb02e1501) | Aug 27, 2023 |
| Lenovo        | ThinkPad X250 20CLS0MN0A    | [4cfb3bf1b1](https://linux-hardware.org/?probe=4cfb3bf1b1) | Aug 27, 2023 |
| ASUSTek       | K54HR                       | [28217feff7](https://linux-hardware.org/?probe=28217feff7) | Aug 27, 2023 |
| Dell          | Inspiron 17 7000 Series ... | [7f67a243d7](https://linux-hardware.org/?probe=7f67a243d7) | Aug 27, 2023 |
| HP            | Compaq 6730b (NB025EA#AB... | [3f742c8393](https://linux-hardware.org/?probe=3f742c8393) | Aug 27, 2023 |
| HP            | Compaq 6730b (NB025EA#AB... | [3b462ade1a](https://linux-hardware.org/?probe=3b462ade1a) | Aug 27, 2023 |
| HP            | 250 G1                      | [27baf9b755](https://linux-hardware.org/?probe=27baf9b755) | Aug 27, 2023 |
| HP            | EliteBook 2540p             | [6641de7018](https://linux-hardware.org/?probe=6641de7018) | Aug 27, 2023 |
| Apple         | MacBookPro16,2              | [f153f48649](https://linux-hardware.org/?probe=f153f48649) | Aug 27, 2023 |
| HP            | 650                         | [ed399f8cfb](https://linux-hardware.org/?probe=ed399f8cfb) | Aug 27, 2023 |
| ASUSTek       | X550CL                      | [679808ec60](https://linux-hardware.org/?probe=679808ec60) | Aug 26, 2023 |
| Lenovo        | ThinkPad X250 20CLS1JN00    | [e8e1a3d429](https://linux-hardware.org/?probe=e8e1a3d429) | Aug 26, 2023 |
| Lenovo        | ThinkPad T470 20HES58A1L    | [b1fe190515](https://linux-hardware.org/?probe=b1fe190515) | Aug 26, 2023 |
| Lenovo        | ThinkPad T470 20HES58A1L    | [bc1cdf2ce7](https://linux-hardware.org/?probe=bc1cdf2ce7) | Aug 26, 2023 |
| Lenovo        | ThinkPad T410 2537VFQ       | [d8b8b7565b](https://linux-hardware.org/?probe=d8b8b7565b) | Aug 26, 2023 |
| HP            | 250 G1                      | [d2989d3be0](https://linux-hardware.org/?probe=d2989d3be0) | Aug 26, 2023 |
| Dell          | Inspiron 5558               | [8a59de1138](https://linux-hardware.org/?probe=8a59de1138) | Aug 26, 2023 |
| ASUSTek       | K54HR                       | [55da0d1667](https://linux-hardware.org/?probe=55da0d1667) | Aug 26, 2023 |
| Dell          | Latitude E6410              | [20134aee31](https://linux-hardware.org/?probe=20134aee31) | Aug 25, 2023 |
| Dell          | Latitude E5520              | [6e27e77275](https://linux-hardware.org/?probe=6e27e77275) | Aug 25, 2023 |
| Acer          | Nitro AN515-45              | [de7752b138](https://linux-hardware.org/?probe=de7752b138) | Aug 25, 2023 |
| Fujitsu       | LIFEBOOK A555               | [1dc34b7cc5](https://linux-hardware.org/?probe=1dc34b7cc5) | Aug 25, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [7d90deb5b1](https://linux-hardware.org/?probe=7d90deb5b1) | Aug 25, 2023 |
| Mediacom      | GTZS                        | [8b40b2b9fc](https://linux-hardware.org/?probe=8b40b2b9fc) | Aug 24, 2023 |
| Dell          | Latitude E6220              | [6afbb8e146](https://linux-hardware.org/?probe=6afbb8e146) | Aug 24, 2023 |
| HP            | ProBook 450 G1              | [1bb6f8d738](https://linux-hardware.org/?probe=1bb6f8d738) | Aug 24, 2023 |
| Gigabyte      | G5 MD                       | [74fe0374b3](https://linux-hardware.org/?probe=74fe0374b3) | Aug 23, 2023 |
| Dell          | Precision M6600             | [60acc9bcb0](https://linux-hardware.org/?probe=60acc9bcb0) | Aug 23, 2023 |
| HP            | Presario CQ57               | [bfc59ff9cd](https://linux-hardware.org/?probe=bfc59ff9cd) | Aug 22, 2023 |
| ASUSTek       | K55A                        | [090e4d0a73](https://linux-hardware.org/?probe=090e4d0a73) | Aug 20, 2023 |
| Dell          | Latitude E6230              | [7888184dd0](https://linux-hardware.org/?probe=7888184dd0) | Aug 19, 2023 |
| Dell          | Latitude E6230              | [1672d92536](https://linux-hardware.org/?probe=1672d92536) | Aug 19, 2023 |
| HP            | Notebook                    | [661cb258ef](https://linux-hardware.org/?probe=661cb258ef) | Aug 19, 2023 |
| Acer          | Swift SF114-32              | [c6f3f044c9](https://linux-hardware.org/?probe=c6f3f044c9) | Aug 19, 2023 |
| Acer          | Swift SF114-32              | [9734816ff1](https://linux-hardware.org/?probe=9734816ff1) | Aug 19, 2023 |
| Dell          | Precision M6600             | [15df8fbaaf](https://linux-hardware.org/?probe=15df8fbaaf) | Aug 18, 2023 |
| ASUSTek       | UX331UA                     | [b48511c64c](https://linux-hardware.org/?probe=b48511c64c) | Aug 16, 2023 |
| ASUSTek       | X550LN                      | [810d33b380](https://linux-hardware.org/?probe=810d33b380) | Aug 16, 2023 |
| Dell          | Latitude E6410              | [9cc0b91505](https://linux-hardware.org/?probe=9cc0b91505) | Aug 14, 2023 |
| HP            | 250 G5 Notebook PC          | [d5b2c3b80a](https://linux-hardware.org/?probe=d5b2c3b80a) | Aug 14, 2023 |
| Fujitsu       | LIFEBOOK A3510              | [3e830ffabc](https://linux-hardware.org/?probe=3e830ffabc) | Aug 12, 2023 |
| Acer          | Aspire E1-532               | [84cbdf027b](https://linux-hardware.org/?probe=84cbdf027b) | Aug 12, 2023 |
| Dell          | Latitude E6430              | [8037585070](https://linux-hardware.org/?probe=8037585070) | Aug 12, 2023 |
| ASUSTek       | K55A                        | [bf260cea2c](https://linux-hardware.org/?probe=bf260cea2c) | Aug 11, 2023 |
| Acer          | Aspire ES1-111M             | [3c7140c389](https://linux-hardware.org/?probe=3c7140c389) | Aug 11, 2023 |
| HP            | Notebook                    | [59e006f729](https://linux-hardware.org/?probe=59e006f729) | Aug 09, 2023 |
| ASUSTek       | X540LJ                      | [e28870563c](https://linux-hardware.org/?probe=e28870563c) | Aug 09, 2023 |
| Lenovo        | ThinkPad T470 20HES0FW00    | [914ff5745c](https://linux-hardware.org/?probe=914ff5745c) | Aug 08, 2023 |
| Google        | Dragonair                   | [45d7954a65](https://linux-hardware.org/?probe=45d7954a65) | Aug 08, 2023 |
| Google        | Dragonair                   | [d78af70cf3](https://linux-hardware.org/?probe=d78af70cf3) | Aug 08, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [6601d0d136](https://linux-hardware.org/?probe=6601d0d136) | Aug 07, 2023 |
| HP            | Notebook                    | [5cfbf14023](https://linux-hardware.org/?probe=5cfbf14023) | Aug 07, 2023 |
| Valve         | Jupiter                     | [96b8677500](https://linux-hardware.org/?probe=96b8677500) | Aug 05, 2023 |
| Dell          | Inspiron 15-3567            | [cf49ab1496](https://linux-hardware.org/?probe=cf49ab1496) | Aug 04, 2023 |
| Dell          | Inspiron 15-3567            | [49e694bb22](https://linux-hardware.org/?probe=49e694bb22) | Aug 04, 2023 |
| Lenovo        | V15-ADA 82C7                | [effe3c3d6d](https://linux-hardware.org/?probe=effe3c3d6d) | Aug 04, 2023 |
| Dell          | Latitude E6420              | [4f67a219dc](https://linux-hardware.org/?probe=4f67a219dc) | Aug 04, 2023 |
| HP            | Laptop 17-ak0xx             | [30b14bc4f6](https://linux-hardware.org/?probe=30b14bc4f6) | Aug 04, 2023 |
| HP            | Laptop 17-ak0xx             | [0e36ac41e4](https://linux-hardware.org/?probe=0e36ac41e4) | Aug 04, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [39fbf6393c](https://linux-hardware.org/?probe=39fbf6393c) | Aug 03, 2023 |
| Acer          | Aspire ES1-533              | [4c45ace98b](https://linux-hardware.org/?probe=4c45ace98b) | Aug 03, 2023 |
| Acer          | Aspire ES1-533              | [b7ffeb681e](https://linux-hardware.org/?probe=b7ffeb681e) | Aug 03, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [a6c2e042e4](https://linux-hardware.org/?probe=a6c2e042e4) | Aug 03, 2023 |
| ASUSTek       | X541NA                      | [b8ece2fce1](https://linux-hardware.org/?probe=b8ece2fce1) | Aug 03, 2023 |
| Fujitsu       | LIFEBOOK A3510              | [7281304bf0](https://linux-hardware.org/?probe=7281304bf0) | Aug 02, 2023 |
| HP            | Notebook                    | [b73fa31837](https://linux-hardware.org/?probe=b73fa31837) | Aug 02, 2023 |
| Lenovo        | G580 20150                  | [8aaca0803f](https://linux-hardware.org/?probe=8aaca0803f) | Jul 31, 2023 |
| HP            | EliteBook 860 16 inch G1... | [9ce45f234a](https://linux-hardware.org/?probe=9ce45f234a) | Jul 31, 2023 |
| HP            | Notebook                    | [329c725795](https://linux-hardware.org/?probe=329c725795) | Jul 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [5bf8462b77](https://linux-hardware.org/?probe=5bf8462b77) | Jul 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [250fc62328](https://linux-hardware.org/?probe=250fc62328) | Jul 30, 2023 |
| Dell          | Inspiron 17 7000 Series ... | [c3b01ce24d](https://linux-hardware.org/?probe=c3b01ce24d) | Jul 30, 2023 |
| Dell          | Inspiron 17 7000 Series ... | [8e26feba38](https://linux-hardware.org/?probe=8e26feba38) | Jul 30, 2023 |
| Fujitsu       | LIFEBOOK A512               | [7bcd0d7683](https://linux-hardware.org/?probe=7bcd0d7683) | Jul 30, 2023 |
| Dell          | Inspiron 7737               | [6fd92e6150](https://linux-hardware.org/?probe=6fd92e6150) | Jul 29, 2023 |
| ASUSTek       | X550CL                      | [3c326304ab](https://linux-hardware.org/?probe=3c326304ab) | Jul 29, 2023 |
| ASUSTek       | X550CL                      | [4e19477a40](https://linux-hardware.org/?probe=4e19477a40) | Jul 29, 2023 |
| Fujitsu       | LIFEBOOK A512               | [404f75d04c](https://linux-hardware.org/?probe=404f75d04c) | Jul 28, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [19d341d49d](https://linux-hardware.org/?probe=19d341d49d) | Jul 28, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [a7c322fa40](https://linux-hardware.org/?probe=a7c322fa40) | Jul 28, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [32b57e4adb](https://linux-hardware.org/?probe=32b57e4adb) | Jul 26, 2023 |
| Lenovo        | ThinkPad T500 2056CL8       | [180a80b4fe](https://linux-hardware.org/?probe=180a80b4fe) | Jul 26, 2023 |
| Acer          | Aspire A515-45              | [58d8bbebcd](https://linux-hardware.org/?probe=58d8bbebcd) | Jul 26, 2023 |
| HP            | Presario CQ56               | [e0e6c2bce2](https://linux-hardware.org/?probe=e0e6c2bce2) | Jul 26, 2023 |
| HP            | Presario CQ56               | [21c97fcc9c](https://linux-hardware.org/?probe=21c97fcc9c) | Jul 26, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [1711396786](https://linux-hardware.org/?probe=1711396786) | Jul 25, 2023 |
| Apple         | MacBookPro5,2               | [e367e06cac](https://linux-hardware.org/?probe=e367e06cac) | Jul 25, 2023 |
| Toshiba       | Satellite C660              | [11a6a3a607](https://linux-hardware.org/?probe=11a6a3a607) | Jul 23, 2023 |
| Acer          | Aspire ES1-571              | [8f2c838141](https://linux-hardware.org/?probe=8f2c838141) | Jul 22, 2023 |
| ASUSTek       | X550CL                      | [c4da72acde](https://linux-hardware.org/?probe=c4da72acde) | Jul 21, 2023 |
| ASUSTek       | X550CL                      | [2d8ae98d9c](https://linux-hardware.org/?probe=2d8ae98d9c) | Jul 21, 2023 |
| Acer          | Aspire ES1-571              | [e022b7bd64](https://linux-hardware.org/?probe=e022b7bd64) | Jul 21, 2023 |
| Dell          | Latitude E6420              | [35d8d85f3c](https://linux-hardware.org/?probe=35d8d85f3c) | Jul 21, 2023 |
| Dell          | Inspiron 7737               | [1faafe201d](https://linux-hardware.org/?probe=1faafe201d) | Jul 19, 2023 |
| Dell          | Inspiron 15-3567            | [4b0ce11ac5](https://linux-hardware.org/?probe=4b0ce11ac5) | Jul 18, 2023 |
| Dell          | Inspiron 15-3567            | [4f7745f5de](https://linux-hardware.org/?probe=4f7745f5de) | Jul 18, 2023 |
| Acer          | Aspire 8930                 | [8b9534387b](https://linux-hardware.org/?probe=8b9534387b) | Jul 17, 2023 |
| Dell          | Inspiron 17 7000 Series ... | [b6925518be](https://linux-hardware.org/?probe=b6925518be) | Jul 16, 2023 |
| HP            | EliteBook 8570w             | [05a330fa6c](https://linux-hardware.org/?probe=05a330fa6c) | Jul 16, 2023 |
| Acer          | Aspire E5-573G              | [3cc36162b8](https://linux-hardware.org/?probe=3cc36162b8) | Jul 16, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [60947b35a4](https://linux-hardware.org/?probe=60947b35a4) | Jul 16, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [856a25b9d5](https://linux-hardware.org/?probe=856a25b9d5) | Jul 16, 2023 |
| Dell          | Inspiron 17 7000 Series ... | [1ccdf38dfa](https://linux-hardware.org/?probe=1ccdf38dfa) | Jul 16, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | [71045dea53](https://linux-hardware.org/?probe=71045dea53) | Jul 16, 2023 |
| Hungaro Fl... | Navon Loop 360              | [b4325e403a](https://linux-hardware.org/?probe=b4325e403a) | Jul 15, 2023 |
| Lenovo        | ThinkPad R400 7440EL1       | [8cc38e55a2](https://linux-hardware.org/?probe=8cc38e55a2) | Jul 15, 2023 |
| Lenovo        | ThinkPad R400 7440EL1       | [c0101c7ae1](https://linux-hardware.org/?probe=c0101c7ae1) | Jul 15, 2023 |
| Acer          | Aspire 6930G                | [ba12b5ff3e](https://linux-hardware.org/?probe=ba12b5ff3e) | Jul 14, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [2b75a3a2b7](https://linux-hardware.org/?probe=2b75a3a2b7) | Jul 13, 2023 |
| RM            | Mobile ONE WIDESCREEN       | [34e242c377](https://linux-hardware.org/?probe=34e242c377) | Jul 13, 2023 |
| RM            | Mobile ONE WIDESCREEN       | [bc67d71f5f](https://linux-hardware.org/?probe=bc67d71f5f) | Jul 13, 2023 |
| Dell          | G3 3590                     | [089bfa3da7](https://linux-hardware.org/?probe=089bfa3da7) | Jul 13, 2023 |
| HP            | EliteBook 8570w             | [5d1ed4c0a4](https://linux-hardware.org/?probe=5d1ed4c0a4) | Jul 12, 2023 |
| Fujitsu       | LIFEBOOK U745               | [c23f2219b4](https://linux-hardware.org/?probe=c23f2219b4) | Jul 12, 2023 |
| Fujitsu       | LIFEBOOK U745               | [e169b67c63](https://linux-hardware.org/?probe=e169b67c63) | Jul 12, 2023 |
| Toshiba       | Satellite C55-A-1NV         | [8528943b9e](https://linux-hardware.org/?probe=8528943b9e) | Jul 11, 2023 |
| Toshiba       | Satellite C55-A-1NV         | [1f9c336539](https://linux-hardware.org/?probe=1f9c336539) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [ecc4006807](https://linux-hardware.org/?probe=ecc4006807) | Jul 11, 2023 |
| HP            | ProBook 4730s               | [0b6a6c7260](https://linux-hardware.org/?probe=0b6a6c7260) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [732d09609d](https://linux-hardware.org/?probe=732d09609d) | Jul 10, 2023 |
| eMachines     | E725                        | [69e7b54469](https://linux-hardware.org/?probe=69e7b54469) | Jul 10, 2023 |
| eMachines     | E725                        | [307f75ef0a](https://linux-hardware.org/?probe=307f75ef0a) | Jul 09, 2023 |
| Lenovo        | B50-30 20382                | [fe0bc25044](https://linux-hardware.org/?probe=fe0bc25044) | Jul 09, 2023 |
| Lenovo        | B50-30 20382                | [70e2ac254a](https://linux-hardware.org/?probe=70e2ac254a) | Jul 09, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [69c5198a22](https://linux-hardware.org/?probe=69c5198a22) | Jul 08, 2023 |
| eMachines     | E725                        | [c70b217933](https://linux-hardware.org/?probe=c70b217933) | Jul 08, 2023 |
| Dell          | Latitude E6220              | [d853b49fc7](https://linux-hardware.org/?probe=d853b49fc7) | Jul 08, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [393ad4fc5d](https://linux-hardware.org/?probe=393ad4fc5d) | Jul 07, 2023 |
| Lenovo        | 20RD001FHV                  | [79166ca12f](https://linux-hardware.org/?probe=79166ca12f) | Jul 07, 2023 |
| Lenovo        | 20RD001FHV                  | [de3ed49995](https://linux-hardware.org/?probe=de3ed49995) | Jul 07, 2023 |
| Lenovo        | ThinkPad X270 20HMS10600    | [5d03b4b2ad](https://linux-hardware.org/?probe=5d03b4b2ad) | Jul 07, 2023 |
| Sony          | VPCYB3V1E                   | [2dd9b76ce0](https://linux-hardware.org/?probe=2dd9b76ce0) | Jul 06, 2023 |
| Acer          | Aspire E5-575G              | [713b52b0c5](https://linux-hardware.org/?probe=713b52b0c5) | Jul 05, 2023 |
| HP            | EliteBook Folio 9480m       | [d992b0a60f](https://linux-hardware.org/?probe=d992b0a60f) | Jul 05, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [11537fb0f5](https://linux-hardware.org/?probe=11537fb0f5) | Jul 04, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16IAH7 8... | [ad57a8dd50](https://linux-hardware.org/?probe=ad57a8dd50) | Jul 04, 2023 |
| Acer          | Aspire E5-575G              | [fe616ea0ed](https://linux-hardware.org/?probe=fe616ea0ed) | Jul 03, 2023 |
| Dell          | Inspiron 5558               | [22879dbc9e](https://linux-hardware.org/?probe=22879dbc9e) | Jul 03, 2023 |
| Dell          | Inspiron 5558               | [496b83b6b8](https://linux-hardware.org/?probe=496b83b6b8) | Jul 03, 2023 |
| eMachines     | E725                        | [ca2b670023](https://linux-hardware.org/?probe=ca2b670023) | Jul 03, 2023 |
| Dell          | Inspiron 15-3567            | [efa8ecd790](https://linux-hardware.org/?probe=efa8ecd790) | Jul 03, 2023 |
| Dell          | Inspiron 15-3567            | [72af61849b](https://linux-hardware.org/?probe=72af61849b) | Jul 03, 2023 |
| eMachines     | E725                        | [622425a84f](https://linux-hardware.org/?probe=622425a84f) | Jul 02, 2023 |
| Dell          | Inspiron 15-3567            | [ef1c856eb5](https://linux-hardware.org/?probe=ef1c856eb5) | Jul 02, 2023 |
| ASUSTek       | Strix GL704GW_GL704GW       | [cb42a3f59d](https://linux-hardware.org/?probe=cb42a3f59d) | Jul 01, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | [b98b20a82c](https://linux-hardware.org/?probe=b98b20a82c) | Jul 01, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | [6484578658](https://linux-hardware.org/?probe=6484578658) | Jul 01, 2023 |
| HP            | EliteBook 2570p             | [c55a78c98a](https://linux-hardware.org/?probe=c55a78c98a) | Jul 01, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | [55bfc9f544](https://linux-hardware.org/?probe=55bfc9f544) | Jul 01, 2023 |
| HP            | 650                         | [279f48a7df](https://linux-hardware.org/?probe=279f48a7df) | Jul 01, 2023 |
| HP            | Notebook                    | [552c6713e1](https://linux-hardware.org/?probe=552c6713e1) | Jun 30, 2023 |
| LG Electro... | 16Z90P-G.AA55H              | [9d40263129](https://linux-hardware.org/?probe=9d40263129) | Jun 30, 2023 |
| LG Electro... | 16Z90P-G.AA55H              | [4e47d108a0](https://linux-hardware.org/?probe=4e47d108a0) | Jun 29, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA502IV... | [76e11b36e9](https://linux-hardware.org/?probe=76e11b36e9) | Jun 28, 2023 |
| Dell          | Inspiron 15-3567            | [d3f7bcfb2c](https://linux-hardware.org/?probe=d3f7bcfb2c) | Jun 27, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [1efefadbdf](https://linux-hardware.org/?probe=1efefadbdf) | Jun 27, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [e304e9beeb](https://linux-hardware.org/?probe=e304e9beeb) | Jun 27, 2023 |
| Dell          | Inspiron 5558               | [126187748f](https://linux-hardware.org/?probe=126187748f) | Jun 27, 2023 |
| eMachines     | E725                        | [e1ed487442](https://linux-hardware.org/?probe=e1ed487442) | Jun 26, 2023 |
| ASUSTek       | K53SJ                       | [922c017262](https://linux-hardware.org/?probe=922c017262) | Jun 26, 2023 |
| ASUSTek       | K53SJ                       | [fe211e4239](https://linux-hardware.org/?probe=fe211e4239) | Jun 26, 2023 |
| eMachines     | E725                        | [909f61c87a](https://linux-hardware.org/?probe=909f61c87a) | Jun 26, 2023 |
| HP            | Notebook                    | [ce52423528](https://linux-hardware.org/?probe=ce52423528) | Jun 26, 2023 |
| Dell          | Latitude E5470              | [c463ab7b16](https://linux-hardware.org/?probe=c463ab7b16) | Jun 26, 2023 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [604d6b2b6f](https://linux-hardware.org/?probe=604d6b2b6f) | Jun 26, 2023 |
| Lenovo        | Y50-70 20378                | [bf911964a8](https://linux-hardware.org/?probe=bf911964a8) | Jun 26, 2023 |
| Dell          | Inspiron 5558               | [43849169cb](https://linux-hardware.org/?probe=43849169cb) | Jun 25, 2023 |
| Dell          | Latitude E5470              | [e8f8b7e986](https://linux-hardware.org/?probe=e8f8b7e986) | Jun 25, 2023 |
| Dell          | Latitude E5470              | [e218b300b7](https://linux-hardware.org/?probe=e218b300b7) | Jun 25, 2023 |
| HP            | EliteBook 2540p             | [2b3a2327fb](https://linux-hardware.org/?probe=2b3a2327fb) | Jun 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [186b2c5cb7](https://linux-hardware.org/?probe=186b2c5cb7) | Jun 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [84239b2594](https://linux-hardware.org/?probe=84239b2594) | Jun 23, 2023 |
| HP            | Notebook                    | [6710ed8c9c](https://linux-hardware.org/?probe=6710ed8c9c) | Jun 21, 2023 |
| Dell          | Inspiron 5570               | [d661316023](https://linux-hardware.org/?probe=d661316023) | Jun 21, 2023 |
| Dell          | Latitude E6410              | [1d89edd254](https://linux-hardware.org/?probe=1d89edd254) | Jun 20, 2023 |
| Dell          | Latitude E6410              | [5230b985a8](https://linux-hardware.org/?probe=5230b985a8) | Jun 20, 2023 |
| Dell          | Latitude E6400              | [9dca1fab41](https://linux-hardware.org/?probe=9dca1fab41) | Jun 20, 2023 |
| Lenovo        | G585 20137                  | [0a36c0985d](https://linux-hardware.org/?probe=0a36c0985d) | Jun 20, 2023 |
| Lenovo        | G585 20137                  | [0ccace2cfb](https://linux-hardware.org/?probe=0ccace2cfb) | Jun 20, 2023 |
| eMachines     | E725                        | [4317f04272](https://linux-hardware.org/?probe=4317f04272) | Jun 19, 2023 |
| Dell          | Latitude E7470              | [645538d81e](https://linux-hardware.org/?probe=645538d81e) | Jun 19, 2023 |
| Lenovo        | V15-ADA 82C7                | [0423e23a21](https://linux-hardware.org/?probe=0423e23a21) | Jun 19, 2023 |
| Lenovo        | G50-45 80E3                 | [1f1209bd20](https://linux-hardware.org/?probe=1f1209bd20) | Jun 19, 2023 |
| Dell          | Inspiron 7737               | [8ccea52f65](https://linux-hardware.org/?probe=8ccea52f65) | Jun 19, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [bbc5301e6b](https://linux-hardware.org/?probe=bbc5301e6b) | Jun 17, 2023 |
| Dell          | Inspiron 5558               | [a1bb681c50](https://linux-hardware.org/?probe=a1bb681c50) | Jun 17, 2023 |
| ASUSTek       | K54HR                       | [6fd4c94830](https://linux-hardware.org/?probe=6fd4c94830) | Jun 16, 2023 |
| Dell          | Inspiron 15-3567            | [6d154340b0](https://linux-hardware.org/?probe=6d154340b0) | Jun 16, 2023 |
| eMachines     | E725                        | [c2ffc64913](https://linux-hardware.org/?probe=c2ffc64913) | Jun 15, 2023 |
| eMachines     | E725                        | [6a88f4f2be](https://linux-hardware.org/?probe=6a88f4f2be) | Jun 14, 2023 |
| Dell          | Latitude 7390               | [aad70ac5b5](https://linux-hardware.org/?probe=aad70ac5b5) | Jun 14, 2023 |
| Dell          | Latitude 7390               | [b718d8d672](https://linux-hardware.org/?probe=b718d8d672) | Jun 14, 2023 |
| Samsung       | RV410/RV510/S3510/E3510     | [26493eeedc](https://linux-hardware.org/?probe=26493eeedc) | Jun 13, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [03f59dc88a](https://linux-hardware.org/?probe=03f59dc88a) | Jun 13, 2023 |
| Samsung       | RV410/RV510/S3510/E3510     | [e68c648de4](https://linux-hardware.org/?probe=e68c648de4) | Jun 13, 2023 |
| HP            | Laptop 15-dw1xxx            | [058f5805e3](https://linux-hardware.org/?probe=058f5805e3) | Jun 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [8c939c89a3](https://linux-hardware.org/?probe=8c939c89a3) | Jun 13, 2023 |
| Dell          | Latitude E5520              | [a86c677685](https://linux-hardware.org/?probe=a86c677685) | Jun 13, 2023 |
| HP            | 250 G1                      | [f8406758e3](https://linux-hardware.org/?probe=f8406758e3) | Jun 13, 2023 |
| HP            | 250 G1                      | [477f9bbabd](https://linux-hardware.org/?probe=477f9bbabd) | Jun 13, 2023 |
| HP            | Notebook                    | [aa5016380c](https://linux-hardware.org/?probe=aa5016380c) | Jun 13, 2023 |
| Acer          | TravelMate P259-G2-M        | [abc5444c45](https://linux-hardware.org/?probe=abc5444c45) | Jun 12, 2023 |
| Lenovo        | ThinkPad X200 74595FG       | [6d6fb0c276](https://linux-hardware.org/?probe=6d6fb0c276) | Jun 12, 2023 |
| Apple         | MacBookAir5,2               | [4b84ec2ade](https://linux-hardware.org/?probe=4b84ec2ade) | Jun 12, 2023 |
| HP            | Pavilion 17                 | [e6279cb0df](https://linux-hardware.org/?probe=e6279cb0df) | Jun 12, 2023 |
| Dell          | Latitude E6230              | [c46f103733](https://linux-hardware.org/?probe=c46f103733) | Jun 11, 2023 |
| Dell          | Latitude E6230              | [390606f3f6](https://linux-hardware.org/?probe=390606f3f6) | Jun 11, 2023 |
| Dell          | Inspiron 17 7000 Series ... | [43d52c8efe](https://linux-hardware.org/?probe=43d52c8efe) | Jun 11, 2023 |
| HP            | 250 G1                      | [e229888d41](https://linux-hardware.org/?probe=e229888d41) | Jun 11, 2023 |
| Lenovo        | V15-ADA 82C7                | [aee2df0fb7](https://linux-hardware.org/?probe=aee2df0fb7) | Jun 11, 2023 |
| Dell          | Latitude E6400              | [c1f065966d](https://linux-hardware.org/?probe=c1f065966d) | Jun 11, 2023 |
| Dell          | Inspiron 7737               | [eff8eec9d8](https://linux-hardware.org/?probe=eff8eec9d8) | Jun 11, 2023 |
| Acer          | Swift SF314-43              | [823925da4a](https://linux-hardware.org/?probe=823925da4a) | Jun 11, 2023 |
| Acer          | Aspire E5-572G              | [6f58cbafdd](https://linux-hardware.org/?probe=6f58cbafdd) | Jun 10, 2023 |
| Dell          | Inspiron 17 7000 Series ... | [068826c25b](https://linux-hardware.org/?probe=068826c25b) | Jun 10, 2023 |
| Acer          | Nitro AN515-44              | [c74a9048c0](https://linux-hardware.org/?probe=c74a9048c0) | Jun 10, 2023 |
| HP            | 250 G1                      | [1b9c881cae](https://linux-hardware.org/?probe=1b9c881cae) | Jun 10, 2023 |
| HP            | 250 G1                      | [0591407196](https://linux-hardware.org/?probe=0591407196) | Jun 10, 2023 |
| HP            | Pavilion dv6                | [1388a433de](https://linux-hardware.org/?probe=1388a433de) | Jun 10, 2023 |
| Valve         | Jupiter                     | [d2df298764](https://linux-hardware.org/?probe=d2df298764) | Jun 10, 2023 |
| ASUSTek       | K54HR                       | [6eada916c0](https://linux-hardware.org/?probe=6eada916c0) | Jun 10, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [9cb24f9445](https://linux-hardware.org/?probe=9cb24f9445) | Jun 09, 2023 |
| Acer          | Aspire 8930                 | [f8eb3278fe](https://linux-hardware.org/?probe=f8eb3278fe) | Jun 09, 2023 |
| Dell          | Inspiron 7737               | [6f7077634a](https://linux-hardware.org/?probe=6f7077634a) | Jun 08, 2023 |
| Google        | Edgar                       | [bec197cb98](https://linux-hardware.org/?probe=bec197cb98) | Jun 07, 2023 |
| Dell          | Latitude E6420              | [011dadb850](https://linux-hardware.org/?probe=011dadb850) | Jun 07, 2023 |
| Dell          | Latitude E6420              | [a1c7c69a05](https://linux-hardware.org/?probe=a1c7c69a05) | Jun 07, 2023 |
| Lenovo        | ThinkPad X200 74595FG       | [26f1962805](https://linux-hardware.org/?probe=26f1962805) | Jun 07, 2023 |
| HP            | EliteBook 2540p             | [96a6ae8f4d](https://linux-hardware.org/?probe=96a6ae8f4d) | Jun 07, 2023 |
| Apple         | MacBookAir5,2               | [8ef73cacf2](https://linux-hardware.org/?probe=8ef73cacf2) | Jun 07, 2023 |
| Lenovo        | G585 20137                  | [6eeacffa3c](https://linux-hardware.org/?probe=6eeacffa3c) | Jun 07, 2023 |
| HP            | 250 G1                      | [f5c0548f17](https://linux-hardware.org/?probe=f5c0548f17) | Jun 07, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [9afe34cdd8](https://linux-hardware.org/?probe=9afe34cdd8) | Jun 06, 2023 |
| ASUSTek       | K73SJ                       | [a77a12f870](https://linux-hardware.org/?probe=a77a12f870) | Jun 06, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [4c3091f9ff](https://linux-hardware.org/?probe=4c3091f9ff) | Jun 06, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [bb5f9c1964](https://linux-hardware.org/?probe=bb5f9c1964) | Jun 06, 2023 |
| HP            | 250 G1                      | [f6cab30981](https://linux-hardware.org/?probe=f6cab30981) | Jun 06, 2023 |
| eMachines     | E725                        | [4e50fbb5a2](https://linux-hardware.org/?probe=4e50fbb5a2) | Jun 05, 2023 |
| Dell          | Latitude E5520              | [ab87df9910](https://linux-hardware.org/?probe=ab87df9910) | Jun 05, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [e1fabecae3](https://linux-hardware.org/?probe=e1fabecae3) | Jun 04, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [66ed048f40](https://linux-hardware.org/?probe=66ed048f40) | Jun 04, 2023 |
| Lenovo        | V15-ADA 82C7                | [0fb6670b07](https://linux-hardware.org/?probe=0fb6670b07) | Jun 03, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | [bcf794dd14](https://linux-hardware.org/?probe=bcf794dd14) | Jun 03, 2023 |
| Dell          | Inspiron 5558               | [746c0d0644](https://linux-hardware.org/?probe=746c0d0644) | Jun 03, 2023 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [3903b22ffd](https://linux-hardware.org/?probe=3903b22ffd) | Jun 02, 2023 |
| Dell          | Inspiron 5558               | [c747f45c48](https://linux-hardware.org/?probe=c747f45c48) | Jun 02, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [c0d0a7cb50](https://linux-hardware.org/?probe=c0d0a7cb50) | Jun 01, 2023 |
| MSI           | U200                        | [a217267eb0](https://linux-hardware.org/?probe=a217267eb0) | Jun 01, 2023 |
| Fujitsu       | LIFEBOOK A555               | [f7e3bde58c](https://linux-hardware.org/?probe=f7e3bde58c) | Jun 01, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [871cbcbb88](https://linux-hardware.org/?probe=871cbcbb88) | May 31, 2023 |
| HP            | Notebook                    | [7d7934f727](https://linux-hardware.org/?probe=7d7934f727) | May 31, 2023 |
| HP            | Notebook                    | [161aaf4150](https://linux-hardware.org/?probe=161aaf4150) | May 31, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [f0d7ab6b7e](https://linux-hardware.org/?probe=f0d7ab6b7e) | May 31, 2023 |
| Lenovo        | ThinkPad X270 20HMS1RM02    | [8f39bcbb17](https://linux-hardware.org/?probe=8f39bcbb17) | May 30, 2023 |
| ASUSTek       | X550CL                      | [ac1e17e897](https://linux-hardware.org/?probe=ac1e17e897) | May 30, 2023 |
| HP            | Pavilion Laptop 14-ce3xx... | [62764248cb](https://linux-hardware.org/?probe=62764248cb) | May 29, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [8e09d71949](https://linux-hardware.org/?probe=8e09d71949) | May 29, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [deaa4b357c](https://linux-hardware.org/?probe=deaa4b357c) | May 29, 2023 |
| ASUSTek       | VivoBook S13 X330FN         | [e94b6fbf06](https://linux-hardware.org/?probe=e94b6fbf06) | May 29, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [af312b5e91](https://linux-hardware.org/?probe=af312b5e91) | May 29, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [f068d88c01](https://linux-hardware.org/?probe=f068d88c01) | May 27, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | [447ea38d26](https://linux-hardware.org/?probe=447ea38d26) | May 27, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | [57dcd55314](https://linux-hardware.org/?probe=57dcd55314) | May 27, 2023 |
| Acer          | TravelMate 6292             | [0a4cb3e4b3](https://linux-hardware.org/?probe=0a4cb3e4b3) | May 25, 2023 |
| Toshiba       | Satellite M50D-A            | [9f7a16aa7b](https://linux-hardware.org/?probe=9f7a16aa7b) | May 25, 2023 |
| Toshiba       | Satellite M50D-A            | [bbb23b2823](https://linux-hardware.org/?probe=bbb23b2823) | May 25, 2023 |
| HP            | Pavilion 17                 | [792ac6919d](https://linux-hardware.org/?probe=792ac6919d) | May 24, 2023 |
| Fujitsu       | LIFEBOOK A555               | [920a4901d9](https://linux-hardware.org/?probe=920a4901d9) | May 24, 2023 |
| Acer          | Aspire A315-58              | [43069955ee](https://linux-hardware.org/?probe=43069955ee) | May 23, 2023 |
| Unknown       | Unknown                     | [da302bee4e](https://linux-hardware.org/?probe=da302bee4e) | May 23, 2023 |
| HP            | 250 G6 Notebook PC          | [431f2db1fc](https://linux-hardware.org/?probe=431f2db1fc) | May 23, 2023 |
| Lenovo        | V15-ADA 82C7                | [5fff4f66c1](https://linux-hardware.org/?probe=5fff4f66c1) | May 22, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [44b6477648](https://linux-hardware.org/?probe=44b6477648) | May 22, 2023 |
| eMachines     | E725                        | [c75d7eb314](https://linux-hardware.org/?probe=c75d7eb314) | May 22, 2023 |
| eMachines     | E725                        | [f32fb866fa](https://linux-hardware.org/?probe=f32fb866fa) | May 22, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [0ab3a9817b](https://linux-hardware.org/?probe=0ab3a9817b) | May 21, 2023 |
| Lenovo        | V15-ADA 82C7                | [6e859c48e1](https://linux-hardware.org/?probe=6e859c48e1) | May 21, 2023 |
| Dell          | Inspiron 5558               | [958b40f42c](https://linux-hardware.org/?probe=958b40f42c) | May 21, 2023 |
| Dell          | Inspiron 5558               | [5043ac245f](https://linux-hardware.org/?probe=5043ac245f) | May 21, 2023 |
| Sony          | VGN-FW21Z                   | [aac218a1e0](https://linux-hardware.org/?probe=aac218a1e0) | May 20, 2023 |
| Dell          | Inspiron 15-3567            | [7db14b0f6f](https://linux-hardware.org/?probe=7db14b0f6f) | May 20, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U7S... | [2e78e77fef](https://linux-hardware.org/?probe=2e78e77fef) | May 19, 2023 |
| eMachines     | E725                        | [517ba05822](https://linux-hardware.org/?probe=517ba05822) | May 19, 2023 |
| HP            | 250 G2                      | [e3b94752ac](https://linux-hardware.org/?probe=e3b94752ac) | May 19, 2023 |
| Dell          | Latitude D630               | [9526ff1765](https://linux-hardware.org/?probe=9526ff1765) | May 19, 2023 |
| HP            | 625                         | [8e34027a91](https://linux-hardware.org/?probe=8e34027a91) | May 18, 2023 |
| Dell          | Latitude D630               | [7a7497a4b3](https://linux-hardware.org/?probe=7a7497a4b3) | May 18, 2023 |
| Fujitsu       | LIFEBOOK A555               | [400b91098c](https://linux-hardware.org/?probe=400b91098c) | May 18, 2023 |
| Alcor Digi... | Snugbook N1431              | [a04e4c387e](https://linux-hardware.org/?probe=a04e4c387e) | May 17, 2023 |
| Unknown       | Unknown                     | [0323142e79](https://linux-hardware.org/?probe=0323142e79) | May 17, 2023 |
| Unknown       | Unknown                     | [d734e52f59](https://linux-hardware.org/?probe=d734e52f59) | May 17, 2023 |
| Lenovo        | V15-ADA 82C7                | [6856deb5d7](https://linux-hardware.org/?probe=6856deb5d7) | May 16, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [e228d9926b](https://linux-hardware.org/?probe=e228d9926b) | May 16, 2023 |
| HP            | Compaq Presario CQ60        | [e01dbddbd0](https://linux-hardware.org/?probe=e01dbddbd0) | May 16, 2023 |
| HP            | Compaq Presario CQ60        | [72db5ccefc](https://linux-hardware.org/?probe=72db5ccefc) | May 15, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [f286932235](https://linux-hardware.org/?probe=f286932235) | May 15, 2023 |
| Dell          | Latitude 5490               | [0a6ee8c111](https://linux-hardware.org/?probe=0a6ee8c111) | May 14, 2023 |
| eMachines     | E725                        | [32c12bfb05](https://linux-hardware.org/?probe=32c12bfb05) | May 14, 2023 |
| Acer          | Aspire A717-72G             | [1ab0673015](https://linux-hardware.org/?probe=1ab0673015) | May 14, 2023 |
| Acer          | Aspire A717-72G             | [62a46acc18](https://linux-hardware.org/?probe=62a46acc18) | May 14, 2023 |
| eMachines     | E725                        | [8768af826f](https://linux-hardware.org/?probe=8768af826f) | May 14, 2023 |
| Lenovo        | G580 20150                  | [f6cf41154f](https://linux-hardware.org/?probe=f6cf41154f) | May 14, 2023 |
| eMachines     | E725                        | [fed9273467](https://linux-hardware.org/?probe=fed9273467) | May 14, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [ae4ee3c43d](https://linux-hardware.org/?probe=ae4ee3c43d) | May 13, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [0ae54cb7c4](https://linux-hardware.org/?probe=0ae54cb7c4) | May 13, 2023 |
| Dell          | Latitude 5480               | [63cd615fa8](https://linux-hardware.org/?probe=63cd615fa8) | May 13, 2023 |
| HP            | Notebook                    | [9840f334f5](https://linux-hardware.org/?probe=9840f334f5) | May 13, 2023 |
| Fujitsu       | LIFEBOOK E756               | [d0f5ee2781](https://linux-hardware.org/?probe=d0f5ee2781) | May 13, 2023 |
| HP            | Notebook                    | [db9aaf4ce9](https://linux-hardware.org/?probe=db9aaf4ce9) | May 13, 2023 |
| eMachines     | E725                        | [52848aa6bd](https://linux-hardware.org/?probe=52848aa6bd) | May 13, 2023 |
| Toshiba       | Satellite C55-A-1NV         | [d06987bfd6](https://linux-hardware.org/?probe=d06987bfd6) | May 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [a7e9891909](https://linux-hardware.org/?probe=a7e9891909) | May 12, 2023 |
| HP            | Notebook                    | [bc25329bce](https://linux-hardware.org/?probe=bc25329bce) | May 12, 2023 |
| HP            | Notebook                    | [d527d781af](https://linux-hardware.org/?probe=d527d781af) | May 11, 2023 |
| eMachines     | E725                        | [94e51437e6](https://linux-hardware.org/?probe=94e51437e6) | May 11, 2023 |
| Lenovo        | V15-ADA 82C7                | [0c8d19bdf0](https://linux-hardware.org/?probe=0c8d19bdf0) | May 10, 2023 |
| Dell          | Inspiron 5558               | [dbc75c5600](https://linux-hardware.org/?probe=dbc75c5600) | May 10, 2023 |
| Dell          | Inspiron 5558               | [396be908b5](https://linux-hardware.org/?probe=396be908b5) | May 10, 2023 |
| Dell          | Latitude E6440              | [ea902a82a4](https://linux-hardware.org/?probe=ea902a82a4) | May 10, 2023 |
| HP            | 250 G1                      | [09879bd463](https://linux-hardware.org/?probe=09879bd463) | May 10, 2023 |
| Apple         | MacBookAir5,2               | [bd3934d526](https://linux-hardware.org/?probe=bd3934d526) | May 10, 2023 |
| Lenovo        | ThinkPad T440s 20ARS06C0... | [543cce00c7](https://linux-hardware.org/?probe=543cce00c7) | May 09, 2023 |
| Fujitsu       | LIFEBOOK U745               | [7a97cdf93b](https://linux-hardware.org/?probe=7a97cdf93b) | May 09, 2023 |
| Dell          | Inspiron 7737               | [f900658289](https://linux-hardware.org/?probe=f900658289) | May 09, 2023 |
| Fujitsu       | LIFEBOOK E756               | [90bec72fa7](https://linux-hardware.org/?probe=90bec72fa7) | May 09, 2023 |
| Acer          | V5-131                      | [d68eaead66](https://linux-hardware.org/?probe=d68eaead66) | May 08, 2023 |
| Lenovo        | G570 20079                  | [bd15eaa1e6](https://linux-hardware.org/?probe=bd15eaa1e6) | May 08, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [8bbe8f0a3f](https://linux-hardware.org/?probe=8bbe8f0a3f) | May 08, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [ad9af07a7c](https://linux-hardware.org/?probe=ad9af07a7c) | May 08, 2023 |
| eMachines     | E725                        | [bb9c7992f8](https://linux-hardware.org/?probe=bb9c7992f8) | May 08, 2023 |
| HP            | Laptop 15-dw1xxx            | [1f677501c0](https://linux-hardware.org/?probe=1f677501c0) | May 07, 2023 |
| HP            | 650                         | [3ece9ca18a](https://linux-hardware.org/?probe=3ece9ca18a) | May 07, 2023 |
| Acer          | TravelMate P215-52          | [b76e0e7397](https://linux-hardware.org/?probe=b76e0e7397) | May 06, 2023 |
| Acer          | TravelMate P215-52          | [5cad7b7e28](https://linux-hardware.org/?probe=5cad7b7e28) | May 06, 2023 |
| ASUSTek       | K53BY                       | [6a9ae368ba](https://linux-hardware.org/?probe=6a9ae368ba) | May 06, 2023 |
| eMachines     | E725                        | [15807b1086](https://linux-hardware.org/?probe=15807b1086) | May 06, 2023 |
| eMachines     | E725                        | [290d356d4c](https://linux-hardware.org/?probe=290d356d4c) | May 05, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [9a0649d500](https://linux-hardware.org/?probe=9a0649d500) | May 05, 2023 |
| Fujitsu       | LIFEBOOK A555               | [9640ef7fa5](https://linux-hardware.org/?probe=9640ef7fa5) | May 05, 2023 |
| Lenovo        | ThinkPad T500 2056CL8       | [df56d361ef](https://linux-hardware.org/?probe=df56d361ef) | May 05, 2023 |
| ASUSTek       | X550CC                      | [0e338f138d](https://linux-hardware.org/?probe=0e338f138d) | May 04, 2023 |
| ASUSTek       | K54HR                       | [4114d6e81c](https://linux-hardware.org/?probe=4114d6e81c) | May 04, 2023 |
| Lenovo        | G50-30 80G0                 | [b322652461](https://linux-hardware.org/?probe=b322652461) | May 04, 2023 |
| Dell          | Latitude 5490               | [c2d5f80f6e](https://linux-hardware.org/?probe=c2d5f80f6e) | May 04, 2023 |
| Lenovo        | ThinkPad T420 4236W8L       | [aaad7b3a55](https://linux-hardware.org/?probe=aaad7b3a55) | May 04, 2023 |
| Lenovo        | ThinkPad X200 74595FG       | [45035a5981](https://linux-hardware.org/?probe=45035a5981) | May 04, 2023 |
| ASUSTek       | K54HR                       | [77cbfa62cd](https://linux-hardware.org/?probe=77cbfa62cd) | May 04, 2023 |
| Lenovo        | ThinkPad X250 20CLS1JN00    | [438c1a31ea](https://linux-hardware.org/?probe=438c1a31ea) | May 04, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [182df1bb15](https://linux-hardware.org/?probe=182df1bb15) | May 04, 2023 |
| Acer          | Aspire 8930                 | [6e2629de4d](https://linux-hardware.org/?probe=6e2629de4d) | May 03, 2023 |
| Lenovo        | E50-80 80J2                 | [c82dd5d579](https://linux-hardware.org/?probe=c82dd5d579) | May 03, 2023 |
| Dell          | Latitude E5520              | [0861e85947](https://linux-hardware.org/?probe=0861e85947) | May 03, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [7e731cb85c](https://linux-hardware.org/?probe=7e731cb85c) | May 03, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [43e6345cb8](https://linux-hardware.org/?probe=43e6345cb8) | May 03, 2023 |
| Lenovo        | V15-ADA 82C7                | [c8a19f5567](https://linux-hardware.org/?probe=c8a19f5567) | May 02, 2023 |
| Fujitsu       | LIFEBOOK A555               | [2280876e20](https://linux-hardware.org/?probe=2280876e20) | May 02, 2023 |
| Dell          | Inspiron 7737               | [9fcb4f708c](https://linux-hardware.org/?probe=9fcb4f708c) | May 02, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [31e13940be](https://linux-hardware.org/?probe=31e13940be) | May 01, 2023 |
| ASUSTek       | X550CC                      | [cc784397f9](https://linux-hardware.org/?probe=cc784397f9) | May 01, 2023 |
| Valve         | Jupiter                     | [07ef050535](https://linux-hardware.org/?probe=07ef050535) | May 01, 2023 |
| Lenovo        | ThinkPad T420 4236W8L       | [96a8ba3062](https://linux-hardware.org/?probe=96a8ba3062) | May 01, 2023 |
| Lenovo        | ThinkPad T420 4236W8L       | [856577ad04](https://linux-hardware.org/?probe=856577ad04) | May 01, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [f84a692777](https://linux-hardware.org/?probe=f84a692777) | Apr 30, 2023 |
| eMachines     | E725                        | [282c0c9f11](https://linux-hardware.org/?probe=282c0c9f11) | Apr 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [558cde0a43](https://linux-hardware.org/?probe=558cde0a43) | Apr 30, 2023 |
| eMachines     | E725                        | [25da91560d](https://linux-hardware.org/?probe=25da91560d) | Apr 30, 2023 |
| Lenovo        | ThinkPad T420 4236W8L       | [25c6042b4e](https://linux-hardware.org/?probe=25c6042b4e) | Apr 30, 2023 |
| Lenovo        | ThinkPad T420 4236W8L       | [230f3dd04b](https://linux-hardware.org/?probe=230f3dd04b) | Apr 30, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [9d5cd21a8f](https://linux-hardware.org/?probe=9d5cd21a8f) | Apr 30, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [9bb7a9b712](https://linux-hardware.org/?probe=9bb7a9b712) | Apr 30, 2023 |
| Dell          | Inspiron 5558               | [ada78ae33d](https://linux-hardware.org/?probe=ada78ae33d) | Apr 28, 2023 |
| Dell          | Inspiron 5558               | [9c2dd52f1e](https://linux-hardware.org/?probe=9c2dd52f1e) | Apr 28, 2023 |
| ASUSTek       | K52JB                       | [e9237f0d53](https://linux-hardware.org/?probe=e9237f0d53) | Apr 27, 2023 |
| eMachines     | E725                        | [668de483ca](https://linux-hardware.org/?probe=668de483ca) | Apr 27, 2023 |
| Acer          | Swift SF114-32              | [13d7dc019c](https://linux-hardware.org/?probe=13d7dc019c) | Apr 26, 2023 |
| Dell          | Inspiron 5558               | [9dd9301581](https://linux-hardware.org/?probe=9dd9301581) | Apr 26, 2023 |
| Lenovo        | G580 20150                  | [5d8b07dbbd](https://linux-hardware.org/?probe=5d8b07dbbd) | Apr 25, 2023 |
| Dell          | Inspiron 5570               | [dd27aa0575](https://linux-hardware.org/?probe=dd27aa0575) | Apr 25, 2023 |
| Dell          | Inspiron 5570               | [e0eef23b19](https://linux-hardware.org/?probe=e0eef23b19) | Apr 25, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [7d5bd7e8fa](https://linux-hardware.org/?probe=7d5bd7e8fa) | Apr 25, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [24bf298df5](https://linux-hardware.org/?probe=24bf298df5) | Apr 25, 2023 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [b402183807](https://linux-hardware.org/?probe=b402183807) | Apr 24, 2023 |
| Lenovo        | 20RD001FHV                  | [782ded0435](https://linux-hardware.org/?probe=782ded0435) | Apr 24, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | [6b9130ca88](https://linux-hardware.org/?probe=6b9130ca88) | Apr 23, 2023 |
| Dell          | Latitude E6230              | [3ec9acadaa](https://linux-hardware.org/?probe=3ec9acadaa) | Apr 23, 2023 |
| Dell          | Latitude E6230              | [8114b606fb](https://linux-hardware.org/?probe=8114b606fb) | Apr 23, 2023 |
| Lenovo        | ThinkPad T420 4236B87       | [f855722ff3](https://linux-hardware.org/?probe=f855722ff3) | Apr 23, 2023 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [090405a4a7](https://linux-hardware.org/?probe=090405a4a7) | Apr 22, 2023 |
| Alcor Digi... | Snugbook N1431              | [eeb69d730b](https://linux-hardware.org/?probe=eeb69d730b) | Apr 22, 2023 |
| Dell          | Inspiron M5040              | [ae29855106](https://linux-hardware.org/?probe=ae29855106) | Apr 22, 2023 |
| Dell          | Inspiron 5558               | [174aa789ca](https://linux-hardware.org/?probe=174aa789ca) | Apr 22, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [918115dc84](https://linux-hardware.org/?probe=918115dc84) | Apr 21, 2023 |
| Sony          | VPCS13V9E                   | [c0f35fa0d2](https://linux-hardware.org/?probe=c0f35fa0d2) | Apr 21, 2023 |
| Dell          | Latitude D630               | [4e4c4f519b](https://linux-hardware.org/?probe=4e4c4f519b) | Apr 18, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | [bd73c6ceb9](https://linux-hardware.org/?probe=bd73c6ceb9) | Apr 18, 2023 |
| ASUSTek       | K52JB                       | [70a0b986fa](https://linux-hardware.org/?probe=70a0b986fa) | Apr 18, 2023 |
| Fujitsu       | LIFEBOOK U745               | [fd7551020f](https://linux-hardware.org/?probe=fd7551020f) | Apr 17, 2023 |
| Sony          | VPCS13V9E                   | [40d1573897](https://linux-hardware.org/?probe=40d1573897) | Apr 16, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [5ef76fe165](https://linux-hardware.org/?probe=5ef76fe165) | Apr 15, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | [f9b8914504](https://linux-hardware.org/?probe=f9b8914504) | Apr 15, 2023 |
| Fujitsu       | LIFEBOOK U745               | [3c0ca40bc5](https://linux-hardware.org/?probe=3c0ca40bc5) | Apr 15, 2023 |
| Toshiba       | Satellite M50D-A            | [17fc6af63a](https://linux-hardware.org/?probe=17fc6af63a) | Apr 15, 2023 |
| Lenovo        | ThinkPad P52 20MAS1LH00     | [06ba20dc47](https://linux-hardware.org/?probe=06ba20dc47) | Apr 15, 2023 |
| HP            | ProBook 650 G3              | [00526690c9](https://linux-hardware.org/?probe=00526690c9) | Apr 15, 2023 |
| Acer          | Extensa 5635Z               | [b3c99bf352](https://linux-hardware.org/?probe=b3c99bf352) | Apr 14, 2023 |
| eMachines     | E725                        | [bd87462ced](https://linux-hardware.org/?probe=bd87462ced) | Apr 13, 2023 |
| Lenovo        | ThinkPad T420 4236B87       | [6d2971f926](https://linux-hardware.org/?probe=6d2971f926) | Apr 13, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603ZM... | [a8184cfc25](https://linux-hardware.org/?probe=a8184cfc25) | Apr 13, 2023 |
| eMachines     | E725                        | [7cd5cba939](https://linux-hardware.org/?probe=7cd5cba939) | Apr 13, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603ZM... | [e75be02a84](https://linux-hardware.org/?probe=e75be02a84) | Apr 12, 2023 |
| THD           | PX1 01                      | [c2c6b63123](https://linux-hardware.org/?probe=c2c6b63123) | Apr 12, 2023 |
| Dell          | Inspiron 1525               | [50e64adbb3](https://linux-hardware.org/?probe=50e64adbb3) | Apr 12, 2023 |
| THD           | PX1 01                      | [f4efc1c20d](https://linux-hardware.org/?probe=f4efc1c20d) | Apr 12, 2023 |
| Dell          | Latitude D630               | [8c211bb7c5](https://linux-hardware.org/?probe=8c211bb7c5) | Apr 12, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [5662df110d](https://linux-hardware.org/?probe=5662df110d) | Apr 11, 2023 |
| Dell          | Inspiron M5030              | [a5dd0e262b](https://linux-hardware.org/?probe=a5dd0e262b) | Apr 10, 2023 |
| Dell          | Inspiron M5030              | [03fb4c2b22](https://linux-hardware.org/?probe=03fb4c2b22) | Apr 10, 2023 |
| Lenovo        | ThinkPad X201 3680WFQ       | [f90c2d47c7](https://linux-hardware.org/?probe=f90c2d47c7) | Apr 10, 2023 |
| Acer          | Aspire ES1-531              | [f36574c96a](https://linux-hardware.org/?probe=f36574c96a) | Apr 09, 2023 |
| Lenovo        | ThinkPad T61 7659AB7        | [0b2f9a23ee](https://linux-hardware.org/?probe=0b2f9a23ee) | Apr 09, 2023 |
| Dell          | Inspiron 5558               | [57ed286290](https://linux-hardware.org/?probe=57ed286290) | Apr 09, 2023 |
| Lenovo        | ThinkPad T60 2008VW7        | [de0d5654c0](https://linux-hardware.org/?probe=de0d5654c0) | Apr 07, 2023 |
| Dell          | Latitude 5431               | [d85ac2917b](https://linux-hardware.org/?probe=d85ac2917b) | Apr 07, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | [ae224a45a1](https://linux-hardware.org/?probe=ae224a45a1) | Apr 06, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [a451cfcce3](https://linux-hardware.org/?probe=a451cfcce3) | Apr 05, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | [1e40d6be20](https://linux-hardware.org/?probe=1e40d6be20) | Apr 04, 2023 |
| HP            | Notebook                    | [d8951b66b8](https://linux-hardware.org/?probe=d8951b66b8) | Apr 03, 2023 |
| HP            | Notebook                    | [05bdafdb5a](https://linux-hardware.org/?probe=05bdafdb5a) | Apr 03, 2023 |
| HP            | 250 G6 Notebook PC          | [c32ab093ae](https://linux-hardware.org/?probe=c32ab093ae) | Apr 01, 2023 |
| ASUSTek       | K52JB                       | [0e18c3546c](https://linux-hardware.org/?probe=0e18c3546c) | Apr 01, 2023 |
| HP            | Notebook                    | [7b9f1f44c9](https://linux-hardware.org/?probe=7b9f1f44c9) | Mar 31, 2023 |
| HP            | Notebook                    | [ad90621225](https://linux-hardware.org/?probe=ad90621225) | Mar 31, 2023 |
| Lenovo        | ThinkPad T470s 20HGS07D0... | [7a8b075b23](https://linux-hardware.org/?probe=7a8b075b23) | Mar 29, 2023 |
| Dell          | Inspiron 5558               | [796d0b6775](https://linux-hardware.org/?probe=796d0b6775) | Mar 28, 2023 |
| Lenovo        | ThinkPad T420 4236W8L       | [bc301a57a0](https://linux-hardware.org/?probe=bc301a57a0) | Mar 27, 2023 |
| Lenovo        | ThinkPad T420 4236W8L       | [e31b586083](https://linux-hardware.org/?probe=e31b586083) | Mar 27, 2023 |
| Dell          | Inspiron 5558               | [fd675e2bf8](https://linux-hardware.org/?probe=fd675e2bf8) | Mar 27, 2023 |
| ASUSTek       | K56CA                       | [43f064cb46](https://linux-hardware.org/?probe=43f064cb46) | Mar 27, 2023 |
| Toshiba       | Satellite L650              | [5006536f60](https://linux-hardware.org/?probe=5006536f60) | Mar 27, 2023 |
| eMachines     | E725                        | [5212ab8375](https://linux-hardware.org/?probe=5212ab8375) | Mar 26, 2023 |
| eMachines     | E725                        | [8e1945a2c2](https://linux-hardware.org/?probe=8e1945a2c2) | Mar 26, 2023 |
| Dell          | Latitude 5480               | [a663d3bc84](https://linux-hardware.org/?probe=a663d3bc84) | Mar 26, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [bb1915d1c3](https://linux-hardware.org/?probe=bb1915d1c3) | Mar 26, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [23df41ca86](https://linux-hardware.org/?probe=23df41ca86) | Mar 26, 2023 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [8701ff9985](https://linux-hardware.org/?probe=8701ff9985) | Mar 26, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [8a92687be7](https://linux-hardware.org/?probe=8a92687be7) | Mar 26, 2023 |
| Lenovo        | G570 20079                  | [ed6328937a](https://linux-hardware.org/?probe=ed6328937a) | Mar 24, 2023 |
| Dell          | Vostro 3500                 | [a375452089](https://linux-hardware.org/?probe=a375452089) | Mar 23, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [f8f47e3220](https://linux-hardware.org/?probe=f8f47e3220) | Mar 23, 2023 |
| eMachines     | E725                        | [a5d9ff191b](https://linux-hardware.org/?probe=a5d9ff191b) | Mar 23, 2023 |
| eMachines     | E725                        | [4204fbff83](https://linux-hardware.org/?probe=4204fbff83) | Mar 23, 2023 |
| Dell          | Latitude E6420              | [6da9274d93](https://linux-hardware.org/?probe=6da9274d93) | Mar 22, 2023 |
| Lenovo        | ThinkPad X270 20HMS10600    | [5e97d4fdf3](https://linux-hardware.org/?probe=5e97d4fdf3) | Mar 22, 2023 |
| ASUSTek       | X550LN                      | [182b5af958](https://linux-hardware.org/?probe=182b5af958) | Mar 22, 2023 |
| ASUSTek       | X550LN                      | [e46c856c11](https://linux-hardware.org/?probe=e46c856c11) | Mar 22, 2023 |
| THD           | PX1 01                      | [d210243a53](https://linux-hardware.org/?probe=d210243a53) | Mar 20, 2023 |
| THD           | PX1 01                      | [246c888564](https://linux-hardware.org/?probe=246c888564) | Mar 20, 2023 |
| Lenovo        | G50-30 80G0                 | [255de14ecc](https://linux-hardware.org/?probe=255de14ecc) | Mar 19, 2023 |
| Dell          | Inspiron 5558               | [79324bb5ca](https://linux-hardware.org/?probe=79324bb5ca) | Mar 19, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [1ee17b12bd](https://linux-hardware.org/?probe=1ee17b12bd) | Mar 19, 2023 |
| Dell          | Inspiron 5558               | [aad9ecc316](https://linux-hardware.org/?probe=aad9ecc316) | Mar 19, 2023 |
| Acer          | Swift SF113-31              | [f1db5ada96](https://linux-hardware.org/?probe=f1db5ada96) | Mar 18, 2023 |
| Toshiba       | Satellite C50-B             | [338da8730f](https://linux-hardware.org/?probe=338da8730f) | Mar 18, 2023 |
| HP            | Notebook                    | [aa27725a50](https://linux-hardware.org/?probe=aa27725a50) | Mar 18, 2023 |
| HP            | Notebook                    | [a3496c8509](https://linux-hardware.org/?probe=a3496c8509) | Mar 18, 2023 |
| HP            | Laptop 17-ak0xx             | [32fbf8242d](https://linux-hardware.org/?probe=32fbf8242d) | Mar 17, 2023 |
| Dell          | Inspiron 5558               | [b0fa0d95b6](https://linux-hardware.org/?probe=b0fa0d95b6) | Mar 17, 2023 |
| Dell          | Inspiron 5558               | [871677af38](https://linux-hardware.org/?probe=871677af38) | Mar 17, 2023 |
| eMachines     | E725                        | [0ea3d3a0ca](https://linux-hardware.org/?probe=0ea3d3a0ca) | Mar 17, 2023 |
| ASUSTek       | X550LN                      | [105acd2203](https://linux-hardware.org/?probe=105acd2203) | Mar 16, 2023 |
| Dell          | Inspiron 14 5425            | [1128b14745](https://linux-hardware.org/?probe=1128b14745) | Mar 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [b606e7c92f](https://linux-hardware.org/?probe=b606e7c92f) | Mar 16, 2023 |
| Dell          | Inspiron 5559               | [966cfad104](https://linux-hardware.org/?probe=966cfad104) | Mar 15, 2023 |
| ASUSTek       | T100HAN                     | [b8585e81f9](https://linux-hardware.org/?probe=b8585e81f9) | Mar 15, 2023 |
| Dell          | Inspiron 5559               | [2aa85f401e](https://linux-hardware.org/?probe=2aa85f401e) | Mar 15, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [d7fbdbbc9f](https://linux-hardware.org/?probe=d7fbdbbc9f) | Mar 15, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [34a0e74a78](https://linux-hardware.org/?probe=34a0e74a78) | Mar 15, 2023 |
| Sony          | VPCEB4L1E                   | [d91d243c75](https://linux-hardware.org/?probe=d91d243c75) | Mar 14, 2023 |
| Lenovo        | G570 20079                  | [aad6765ba3](https://linux-hardware.org/?probe=aad6765ba3) | Mar 14, 2023 |
| HP            | Laptop 17-ak0xx             | [0acca6eb92](https://linux-hardware.org/?probe=0acca6eb92) | Mar 14, 2023 |
| HP            | EliteBook 840 G1            | [cbb20e87cb](https://linux-hardware.org/?probe=cbb20e87cb) | Mar 14, 2023 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | [7f06c80526](https://linux-hardware.org/?probe=7f06c80526) | Mar 14, 2023 |
| HP            | ZBook Studio G4             | [2e04fad893](https://linux-hardware.org/?probe=2e04fad893) | Mar 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [ad61830c15](https://linux-hardware.org/?probe=ad61830c15) | Mar 12, 2023 |
| Insyde        | BayTrail                    | [8d0337a8ee](https://linux-hardware.org/?probe=8d0337a8ee) | Mar 12, 2023 |
| eMachines     | E725                        | [9a49d6defc](https://linux-hardware.org/?probe=9a49d6defc) | Mar 12, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [3f007adfc7](https://linux-hardware.org/?probe=3f007adfc7) | Mar 10, 2023 |
| Fujitsu       | LIFEBOOK AH530              | [eca94a98c0](https://linux-hardware.org/?probe=eca94a98c0) | Mar 09, 2023 |
| eMachines     | E725                        | [a4a1665906](https://linux-hardware.org/?probe=a4a1665906) | Mar 09, 2023 |
| HP            | Laptop 15s-eq1xxx           | [fc2ee93757](https://linux-hardware.org/?probe=fc2ee93757) | Mar 08, 2023 |
| HP            | Laptop 15s-eq1xxx           | [e1ce357347](https://linux-hardware.org/?probe=e1ce357347) | Mar 08, 2023 |
| eMachines     | E725                        | [8efce0fe6f](https://linux-hardware.org/?probe=8efce0fe6f) | Mar 08, 2023 |
| HP            | Laptop 17-ak0xx             | [cda5fafaf9](https://linux-hardware.org/?probe=cda5fafaf9) | Mar 07, 2023 |
| HP            | Laptop 17-ak0xx             | [c27eecca48](https://linux-hardware.org/?probe=c27eecca48) | Mar 07, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [85701c7290](https://linux-hardware.org/?probe=85701c7290) | Mar 07, 2023 |
| Fujitsu       | LIFEBOOK AH530              | [5f336adb00](https://linux-hardware.org/?probe=5f336adb00) | Mar 07, 2023 |
| Toshiba       | Satellite L650              | [ee9717cba3](https://linux-hardware.org/?probe=ee9717cba3) | Mar 07, 2023 |
| Toshiba       | Satellite L650              | [77f0d6b014](https://linux-hardware.org/?probe=77f0d6b014) | Mar 07, 2023 |
| Toshiba       | Satellite L650              | [267c62f49a](https://linux-hardware.org/?probe=267c62f49a) | Mar 07, 2023 |
| MSI           | Katana GF66 11UD            | [f464d5be92](https://linux-hardware.org/?probe=f464d5be92) | Mar 07, 2023 |
| ASUSTek       | GL552JX                     | [c8cff8908f](https://linux-hardware.org/?probe=c8cff8908f) | Mar 07, 2023 |
| ASUSTek       | ASUS P1512CEA_P1512CEA      | [ef2488509b](https://linux-hardware.org/?probe=ef2488509b) | Mar 06, 2023 |
| Alcor         | SnugBook Q series           | [3b3c4fd9fd](https://linux-hardware.org/?probe=3b3c4fd9fd) | Mar 05, 2023 |
| Lenovo        | Y50-70 20378                | [c564adb32c](https://linux-hardware.org/?probe=c564adb32c) | Mar 04, 2023 |
| HP            | 650                         | [f595da7b8c](https://linux-hardware.org/?probe=f595da7b8c) | Mar 04, 2023 |
| HP            | 650                         | [9d0b38c967](https://linux-hardware.org/?probe=9d0b38c967) | Mar 04, 2023 |
| Dell          | Inspiron 3584               | [4b6e4a874b](https://linux-hardware.org/?probe=4b6e4a874b) | Mar 04, 2023 |
| HP            | Compaq 6720s                | [b422954b5a](https://linux-hardware.org/?probe=b422954b5a) | Mar 03, 2023 |
| Lenovo        | ThinkPad X270 20HMS10600    | [4bab3eb831](https://linux-hardware.org/?probe=4bab3eb831) | Mar 03, 2023 |
| Lenovo        | ThinkPad X270 20HMS10600    | [da2fc6826a](https://linux-hardware.org/?probe=da2fc6826a) | Mar 01, 2023 |
| Fujitsu Si... | AMILO Li3910                | [f29ead8551](https://linux-hardware.org/?probe=f29ead8551) | Mar 01, 2023 |
| TCL Commun... | 8090                        | [d1f86443c7](https://linux-hardware.org/?probe=d1f86443c7) | Feb 28, 2023 |
| ASUSTek       | Zenbook UX5401ZA_UX5401Z... | [5aad25779a](https://linux-hardware.org/?probe=5aad25779a) | Feb 28, 2023 |
| Acer          | Nitro AN515-51              | [984b6e660d](https://linux-hardware.org/?probe=984b6e660d) | Feb 28, 2023 |
| Lenovo        | ThinkPad X270 20HMS10600    | [3fa4d926e0](https://linux-hardware.org/?probe=3fa4d926e0) | Feb 28, 2023 |
| HP            | Notebook                    | [7e64e6bc1b](https://linux-hardware.org/?probe=7e64e6bc1b) | Feb 27, 2023 |
| Dell          | Latitude 3510               | [de938c4962](https://linux-hardware.org/?probe=de938c4962) | Feb 27, 2023 |
| Acer          | Nitro AN515-51              | [e5fa16c859](https://linux-hardware.org/?probe=e5fa16c859) | Feb 25, 2023 |
| HP            | Unknown                     | [18a8d556cb](https://linux-hardware.org/?probe=18a8d556cb) | Feb 25, 2023 |
| Dell          | Vostro 14-5459              | [1f96898a48](https://linux-hardware.org/?probe=1f96898a48) | Feb 25, 2023 |
| HP            | Unknown                     | [dc26b08a65](https://linux-hardware.org/?probe=dc26b08a65) | Feb 25, 2023 |
| ASUSTek       | X550LN                      | [6ebe283b1c](https://linux-hardware.org/?probe=6ebe283b1c) | Feb 25, 2023 |
| Dell          | XPS 13 9310                 | [1b60ef35ce](https://linux-hardware.org/?probe=1b60ef35ce) | Feb 24, 2023 |
| Lenovo        | ThinkPad T410 2537CS0       | [8d4b399341](https://linux-hardware.org/?probe=8d4b399341) | Feb 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [4d2d4ca208](https://linux-hardware.org/?probe=4d2d4ca208) | Feb 23, 2023 |
| Lenovo        | ThinkPad E14 20RA0036HV     | [eef601ff61](https://linux-hardware.org/?probe=eef601ff61) | Feb 23, 2023 |
| HP            | Laptop 15-dw1xxx            | [bf47e38ec4](https://linux-hardware.org/?probe=bf47e38ec4) | Feb 22, 2023 |
| Acer          | Nitro AN515-51              | [c2be84fb6c](https://linux-hardware.org/?probe=c2be84fb6c) | Feb 21, 2023 |
| HP            | 250 G3                      | [638d8fa72b](https://linux-hardware.org/?probe=638d8fa72b) | Feb 21, 2023 |
| HP            | 250 G3                      | [eaf1a8a9ca](https://linux-hardware.org/?probe=eaf1a8a9ca) | Feb 21, 2023 |
| HP            | Laptop 17-ak0xx             | [d282ac975d](https://linux-hardware.org/?probe=d282ac975d) | Feb 21, 2023 |
| eMachines     | E725                        | [d982b1aa72](https://linux-hardware.org/?probe=d982b1aa72) | Feb 20, 2023 |
| Acer          | Nitro AN515-51              | [5df682e5d6](https://linux-hardware.org/?probe=5df682e5d6) | Feb 20, 2023 |
| HP            | EliteBook 735 G5            | [19d29283ed](https://linux-hardware.org/?probe=19d29283ed) | Feb 20, 2023 |
| HP            | EliteBook 735 G5            | [8d1bb46519](https://linux-hardware.org/?probe=8d1bb46519) | Feb 20, 2023 |
| ASUSTek       | K52F                        | [2cbb8f3f38](https://linux-hardware.org/?probe=2cbb8f3f38) | Feb 20, 2023 |
| ASUSTek       | X541NA                      | [b9ddd17e6c](https://linux-hardware.org/?probe=b9ddd17e6c) | Feb 19, 2023 |
| HP            | Laptop 15-dw1xxx            | [22dfb58516](https://linux-hardware.org/?probe=22dfb58516) | Feb 19, 2023 |
| Toshiba       | Satellite Pro L300          | [c2168db120](https://linux-hardware.org/?probe=c2168db120) | Feb 18, 2023 |
| Dell          | Inspiron 5558               | [40f71233c4](https://linux-hardware.org/?probe=40f71233c4) | Feb 17, 2023 |
| Dell          | Inspiron 5558               | [44e9817292](https://linux-hardware.org/?probe=44e9817292) | Feb 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [a4f7bc0d84](https://linux-hardware.org/?probe=a4f7bc0d84) | Feb 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [a6bde6db60](https://linux-hardware.org/?probe=a6bde6db60) | Feb 17, 2023 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [6d7740ca9d](https://linux-hardware.org/?probe=6d7740ca9d) | Feb 17, 2023 |
| HP            | EliteBook 840 G5            | [fb9eb2345d](https://linux-hardware.org/?probe=fb9eb2345d) | Feb 16, 2023 |
| Fujitsu       | LIFEBOOK U745               | [4f0e88ce52](https://linux-hardware.org/?probe=4f0e88ce52) | Feb 16, 2023 |
| Fujitsu       | LIFEBOOK U745               | [eac8d6ab9d](https://linux-hardware.org/?probe=eac8d6ab9d) | Feb 16, 2023 |
| HP            | 250 G1                      | [a673746c67](https://linux-hardware.org/?probe=a673746c67) | Feb 16, 2023 |
| HP            | 250 G1                      | [cc5e272ca9](https://linux-hardware.org/?probe=cc5e272ca9) | Feb 16, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [33b1f65ec0](https://linux-hardware.org/?probe=33b1f65ec0) | Feb 15, 2023 |
| Lenovo        | Z710 20250                  | [7b40745c7f](https://linux-hardware.org/?probe=7b40745c7f) | Feb 14, 2023 |
| Lenovo        | Z710 20250                  | [903deba17a](https://linux-hardware.org/?probe=903deba17a) | Feb 14, 2023 |
| HP            | Pavilion dv5                | [fd6bd7275b](https://linux-hardware.org/?probe=fd6bd7275b) | Feb 14, 2023 |
| Fujitsu Si... | STYLISTIC ST5112            | [2334fc688f](https://linux-hardware.org/?probe=2334fc688f) | Feb 14, 2023 |
| Fujitsu Si... | STYLISTIC ST5112            | [e2f49b2fe4](https://linux-hardware.org/?probe=e2f49b2fe4) | Feb 14, 2023 |
| Dell          | Inspiron 15-3567            | [6fe738fa6d](https://linux-hardware.org/?probe=6fe738fa6d) | Feb 13, 2023 |
| Dell          | Inspiron 15-3567            | [122eded37e](https://linux-hardware.org/?probe=122eded37e) | Feb 13, 2023 |
| Dell          | Latitude 5420               | [60cc86374d](https://linux-hardware.org/?probe=60cc86374d) | Feb 12, 2023 |
| Dell          | Latitude 5420               | [63a576e744](https://linux-hardware.org/?probe=63a576e744) | Feb 12, 2023 |
| Acer          | TravelMate 8571             | [609cc404fb](https://linux-hardware.org/?probe=609cc404fb) | Feb 12, 2023 |
| HP            | Compaq 6910p                | [328acaf5ee](https://linux-hardware.org/?probe=328acaf5ee) | Feb 12, 2023 |
| ASUSTek       | K52F                        | [ee35b00a7e](https://linux-hardware.org/?probe=ee35b00a7e) | Feb 12, 2023 |
| ASUSTek       | X541UAK                     | [e27e733bc0](https://linux-hardware.org/?probe=e27e733bc0) | Feb 12, 2023 |
| ASUSTek       | K52F                        | [364c41f9aa](https://linux-hardware.org/?probe=364c41f9aa) | Feb 11, 2023 |
| HP            | Laptop 14s-fq0xxx           | [eb1f7dfd26](https://linux-hardware.org/?probe=eb1f7dfd26) | Feb 10, 2023 |
| Dell          | Latitude E6230              | [d0a04b130a](https://linux-hardware.org/?probe=d0a04b130a) | Feb 09, 2023 |
| Dell          | Latitude E6230              | [11a1ba46f3](https://linux-hardware.org/?probe=11a1ba46f3) | Feb 09, 2023 |
| MSI           | GX70 3CC                    | [c9abc5f038](https://linux-hardware.org/?probe=c9abc5f038) | Feb 07, 2023 |
| Acer          | Aspire A515-57G             | [dd6c2cbcc6](https://linux-hardware.org/?probe=dd6c2cbcc6) | Feb 07, 2023 |
| Acer          | Aspire A515-57G             | [470857588f](https://linux-hardware.org/?probe=470857588f) | Feb 07, 2023 |
| ASUSTek       | X541UAK                     | [62acbef04d](https://linux-hardware.org/?probe=62acbef04d) | Feb 07, 2023 |
| HP            | Unknown                     | [eb01c0393d](https://linux-hardware.org/?probe=eb01c0393d) | Feb 07, 2023 |
| HP            | Unknown                     | [db607a1e03](https://linux-hardware.org/?probe=db607a1e03) | Feb 07, 2023 |
| Lenovo        | ThinkPad T490 20N3S11B0V    | [3b35d51bfb](https://linux-hardware.org/?probe=3b35d51bfb) | Feb 06, 2023 |
| Lenovo        | ThinkPad T410 2537CS0       | [8b6fbfa8f5](https://linux-hardware.org/?probe=8b6fbfa8f5) | Feb 04, 2023 |
| Acer          | Aspire A515-51G             | [2b37c84303](https://linux-hardware.org/?probe=2b37c84303) | Feb 04, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [a9e735ed75](https://linux-hardware.org/?probe=a9e735ed75) | Feb 03, 2023 |
| Dell          | Latitude D630               | [a1ea4874cf](https://linux-hardware.org/?probe=a1ea4874cf) | Feb 03, 2023 |
| Dell          | Vostro 15-3568              | [caf63a9d0f](https://linux-hardware.org/?probe=caf63a9d0f) | Feb 02, 2023 |
| Dell          | Latitude D630               | [7f34868246](https://linux-hardware.org/?probe=7f34868246) | Feb 02, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [6294616fc6](https://linux-hardware.org/?probe=6294616fc6) | Feb 01, 2023 |
| Dell          | Inspiron 7737               | [fb42f48fbe](https://linux-hardware.org/?probe=fb42f48fbe) | Feb 01, 2023 |
| eMachines     | E725                        | [4b1805b3f6](https://linux-hardware.org/?probe=4b1805b3f6) | Feb 01, 2023 |
| HP            | EliteBook 8570p             | [2f7f3a5b93](https://linux-hardware.org/?probe=2f7f3a5b93) | Feb 01, 2023 |
| Apple         | MacBookAir5,2               | [8a90f64e68](https://linux-hardware.org/?probe=8a90f64e68) | Feb 01, 2023 |
| HP            | 250 G1                      | [41f3eccf2e](https://linux-hardware.org/?probe=41f3eccf2e) | Feb 01, 2023 |
| Apple         | MacBookAir5,2               | [2bdd007ce6](https://linux-hardware.org/?probe=2bdd007ce6) | Feb 01, 2023 |
| HP            | 250 G1                      | [345cb01bcc](https://linux-hardware.org/?probe=345cb01bcc) | Feb 01, 2023 |
| Acer          | Aspire A315-21G             | [1a3af834c9](https://linux-hardware.org/?probe=1a3af834c9) | Feb 01, 2023 |
| Acer          | Aspire A315-21G             | [78f5b5c42b](https://linux-hardware.org/?probe=78f5b5c42b) | Feb 01, 2023 |
| Lenovo        | Y50-70 20378                | [04c77927f5](https://linux-hardware.org/?probe=04c77927f5) | Jan 31, 2023 |
| Lenovo        | Y50-70 20378                | [5dc21f30b5](https://linux-hardware.org/?probe=5dc21f30b5) | Jan 31, 2023 |
| Lenovo        | G580 20150                  | [339aef175f](https://linux-hardware.org/?probe=339aef175f) | Jan 30, 2023 |
| Lenovo        | G580 20150                  | [e0b08d335b](https://linux-hardware.org/?probe=e0b08d335b) | Jan 30, 2023 |
| Lenovo        | ThinkPad W510 431924G       | [c899463c77](https://linux-hardware.org/?probe=c899463c77) | Jan 30, 2023 |
| HP            | ProBook 4520s               | [6a16110b08](https://linux-hardware.org/?probe=6a16110b08) | Jan 29, 2023 |
| HP            | ProBook 4520s               | [e973aeb114](https://linux-hardware.org/?probe=e973aeb114) | Jan 29, 2023 |
| Samsung       | N102S                       | [c23908cf42](https://linux-hardware.org/?probe=c23908cf42) | Jan 28, 2023 |
| Lenovo        | ThinkPad T480 20L6SF8C00    | [4ab453f835](https://linux-hardware.org/?probe=4ab453f835) | Jan 28, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [c6770f3828](https://linux-hardware.org/?probe=c6770f3828) | Jan 28, 2023 |
| HP            | ProBook 430 G6              | [24fd7df5b6](https://linux-hardware.org/?probe=24fd7df5b6) | Jan 28, 2023 |
| Lenovo        | G580 20150                  | [7597b19143](https://linux-hardware.org/?probe=7597b19143) | Jan 26, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [4804425adc](https://linux-hardware.org/?probe=4804425adc) | Jan 25, 2023 |
| Acer          | Aspire A517-53G             | [2a1ad07cce](https://linux-hardware.org/?probe=2a1ad07cce) | Jan 25, 2023 |
| Acer          | Aspire A515-57G             | [2b83e8779f](https://linux-hardware.org/?probe=2b83e8779f) | Jan 25, 2023 |
| Acer          | Aspire A515-57G             | [cc3599afd2](https://linux-hardware.org/?probe=cc3599afd2) | Jan 24, 2023 |
| Dell          | Latitude 5480               | [0e21cc929a](https://linux-hardware.org/?probe=0e21cc929a) | Jan 24, 2023 |
| UMAX          | VisionBook 14Wr Plus        | [16e64883d7](https://linux-hardware.org/?probe=16e64883d7) | Jan 24, 2023 |
| HP            | EliteBook Folio 9480m       | [39c54a5f09](https://linux-hardware.org/?probe=39c54a5f09) | Jan 24, 2023 |
| HP            | EliteBook Folio 9480m       | [ae139e78a0](https://linux-hardware.org/?probe=ae139e78a0) | Jan 22, 2023 |
| HP            | EliteBook Folio 9480m       | [d43d26ff9f](https://linux-hardware.org/?probe=d43d26ff9f) | Jan 22, 2023 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [53fb561c53](https://linux-hardware.org/?probe=53fb561c53) | Jan 21, 2023 |
| Acer          | Aspire A317-33              | [b7147af4f6](https://linux-hardware.org/?probe=b7147af4f6) | Jan 20, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [7aa00b2d9f](https://linux-hardware.org/?probe=7aa00b2d9f) | Jan 19, 2023 |
| Acer          | Nitro AN515-42              | [d6a24ede85](https://linux-hardware.org/?probe=d6a24ede85) | Jan 19, 2023 |
| Dell          | Latitude 5420               | [cb511c0f82](https://linux-hardware.org/?probe=cb511c0f82) | Jan 18, 2023 |
| Lenovo        | Yoga 500-14IHW 80N5         | [e233e8d6d2](https://linux-hardware.org/?probe=e233e8d6d2) | Jan 18, 2023 |
| Acer          | TravelMate 8571             | [2933c64a6d](https://linux-hardware.org/?probe=2933c64a6d) | Jan 15, 2023 |
| Acer          | TravelMate 8571             | [ad01651917](https://linux-hardware.org/?probe=ad01651917) | Jan 15, 2023 |
| HP            | EliteBook 745 G3            | [c20a339ddb](https://linux-hardware.org/?probe=c20a339ddb) | Jan 15, 2023 |
| Acer          | TravelMate B117-M           | [c760a021bf](https://linux-hardware.org/?probe=c760a021bf) | Jan 14, 2023 |
| Acer          | TravelMate B117-M           | [bee982f325](https://linux-hardware.org/?probe=bee982f325) | Jan 14, 2023 |
| HP            | ZBook 17 G3                 | [6c53f137fd](https://linux-hardware.org/?probe=6c53f137fd) | Jan 14, 2023 |
| Dell          | Inspiron 5558               | [798c78aaf7](https://linux-hardware.org/?probe=798c78aaf7) | Jan 14, 2023 |
| ASUSTek       | X550LN                      | [d412367e44](https://linux-hardware.org/?probe=d412367e44) | Jan 13, 2023 |
| ASUSTek       | X550LN                      | [196ba30ef7](https://linux-hardware.org/?probe=196ba30ef7) | Jan 13, 2023 |
| Fujitsu       | LIFEBOOK T730               | [f9ba03526e](https://linux-hardware.org/?probe=f9ba03526e) | Jan 13, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [61f80cd38a](https://linux-hardware.org/?probe=61f80cd38a) | Jan 13, 2023 |
| UMAX          | VisionBook 14Wr Plus        | [10f4ae9765](https://linux-hardware.org/?probe=10f4ae9765) | Jan 12, 2023 |
| UMAX          | VisionBook 14Wr Plus        | [48531d8e05](https://linux-hardware.org/?probe=48531d8e05) | Jan 12, 2023 |
| Fujitsu       | LIFEBOOK U745               | [e3eb62db83](https://linux-hardware.org/?probe=e3eb62db83) | Jan 12, 2023 |
| Fujitsu       | LIFEBOOK U745               | [b36d8e79ea](https://linux-hardware.org/?probe=b36d8e79ea) | Jan 12, 2023 |
| HP            | ProBook 4535s               | [47cd489d8b](https://linux-hardware.org/?probe=47cd489d8b) | Jan 11, 2023 |
| Lenovo        | G50-45 80E3                 | [80f84b2854](https://linux-hardware.org/?probe=80f84b2854) | Jan 11, 2023 |
| HP            | EliteBook 8460p             | [a941237bf3](https://linux-hardware.org/?probe=a941237bf3) | Jan 11, 2023 |
| HP            | EliteBook 2540p             | [9eebe49454](https://linux-hardware.org/?probe=9eebe49454) | Jan 11, 2023 |
| HP            | EliteBook 2540p             | [106e3d9073](https://linux-hardware.org/?probe=106e3d9073) | Jan 11, 2023 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [1ebf7a4a09](https://linux-hardware.org/?probe=1ebf7a4a09) | Jan 11, 2023 |
| Lenovo        | G580 20150                  | [b1fb0a1f64](https://linux-hardware.org/?probe=b1fb0a1f64) | Jan 10, 2023 |
| ASUSTek       | Strix 15 GL503GE            | [07b77ef803](https://linux-hardware.org/?probe=07b77ef803) | Jan 09, 2023 |
| Acer          | A515-44G                    | [0589eb53fa](https://linux-hardware.org/?probe=0589eb53fa) | Jan 08, 2023 |
| HP            | Laptop 17-ak0xx             | [beef7a74d4](https://linux-hardware.org/?probe=beef7a74d4) | Jan 08, 2023 |
| HP            | ProBook 6570b               | [ac7eff1b5e](https://linux-hardware.org/?probe=ac7eff1b5e) | Jan 08, 2023 |
| HP            | ProBook 6570b               | [819a1c02df](https://linux-hardware.org/?probe=819a1c02df) | Jan 08, 2023 |
| HP            | Laptop 17-ak0xx             | [ffed123536](https://linux-hardware.org/?probe=ffed123536) | Jan 07, 2023 |
| HP            | Pavilion 15                 | [f946892969](https://linux-hardware.org/?probe=f946892969) | Jan 07, 2023 |
| Lenovo        | G580 20150                  | [daad153e9a](https://linux-hardware.org/?probe=daad153e9a) | Jan 06, 2023 |
| HP            | 255 G5 Notebook PC          | [7c62a0a238](https://linux-hardware.org/?probe=7c62a0a238) | Jan 06, 2023 |
| Dell          | Inspiron 5558               | [1473e6f0d9](https://linux-hardware.org/?probe=1473e6f0d9) | Jan 06, 2023 |
| Dell          | Inspiron 5558               | [74f479bd3e](https://linux-hardware.org/?probe=74f479bd3e) | Jan 06, 2023 |
| Dell          | Latitude E6420              | [8b590c65fc](https://linux-hardware.org/?probe=8b590c65fc) | Jan 05, 2023 |
| Dell          | Latitude 5430               | [4e8033e0f6](https://linux-hardware.org/?probe=4e8033e0f6) | Jan 05, 2023 |
| Lenovo        | G580 20150                  | [9a16949691](https://linux-hardware.org/?probe=9a16949691) | Jan 05, 2023 |
| Lenovo        | G580 20150                  | [b7119b52a7](https://linux-hardware.org/?probe=b7119b52a7) | Jan 05, 2023 |
| Lenovo        | ThinkPad T410 2537BF9       | [30195a4ca0](https://linux-hardware.org/?probe=30195a4ca0) | Jan 04, 2023 |
| Lenovo        | ThinkPad T410 2537BF9       | [2e29dd8142](https://linux-hardware.org/?probe=2e29dd8142) | Jan 04, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [4247d8d8b0](https://linux-hardware.org/?probe=4247d8d8b0) | Jan 04, 2023 |
| HP            | 255 G5 Notebook PC          | [cdb140b891](https://linux-hardware.org/?probe=cdb140b891) | Jan 03, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [ed9ddacdce](https://linux-hardware.org/?probe=ed9ddacdce) | Jan 01, 2023 |
| Lenovo        | G565 20071                  | [e974b446ae](https://linux-hardware.org/?probe=e974b446ae) | Jan 01, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [cc19d2cf24](https://linux-hardware.org/?probe=cc19d2cf24) | Dec 31, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [e0f696a9b9](https://linux-hardware.org/?probe=e0f696a9b9) | Dec 31, 2022 |
| Lenovo        | ThinkPad T410 2537BF9       | [f83ed1dd39](https://linux-hardware.org/?probe=f83ed1dd39) | Dec 30, 2022 |
| Dell          | G15 5520                    | [2e82f45fb6](https://linux-hardware.org/?probe=2e82f45fb6) | Dec 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [6c00206f7e](https://linux-hardware.org/?probe=6c00206f7e) | Dec 30, 2022 |
| Dell          | Latitude 5480               | [e02be15b45](https://linux-hardware.org/?probe=e02be15b45) | Dec 30, 2022 |
| Dell          | Latitude 5480               | [5afd8e73be](https://linux-hardware.org/?probe=5afd8e73be) | Dec 30, 2022 |
| HP            | EliteBook 2540p             | [279718a62f](https://linux-hardware.org/?probe=279718a62f) | Dec 30, 2022 |
| Dell          | Latitude 5480               | [64aa4b9161](https://linux-hardware.org/?probe=64aa4b9161) | Dec 30, 2022 |
| Dell          | Vostro 1015                 | [fd48487066](https://linux-hardware.org/?probe=fd48487066) | Dec 30, 2022 |
| ASUSTek       | TUF Gaming FX705GM_FX705... | [c286883155](https://linux-hardware.org/?probe=c286883155) | Dec 29, 2022 |
| Dell          | Latitude 5480               | [b578e196dd](https://linux-hardware.org/?probe=b578e196dd) | Dec 29, 2022 |
| Dell          | Latitude E6230              | [a8df3d8262](https://linux-hardware.org/?probe=a8df3d8262) | Dec 29, 2022 |
| Dell          | Latitude E6230              | [a57d2f5ccb](https://linux-hardware.org/?probe=a57d2f5ccb) | Dec 29, 2022 |
| Dell          | Vostro 1015                 | [11e78b0f9b](https://linux-hardware.org/?probe=11e78b0f9b) | Dec 29, 2022 |
| Dell          | Latitude 5480               | [4b2fda33f4](https://linux-hardware.org/?probe=4b2fda33f4) | Dec 28, 2022 |
| Dell          | Latitude 5480               | [abcd3bea2f](https://linux-hardware.org/?probe=abcd3bea2f) | Dec 28, 2022 |
| Acer          | Aspire E5-573G              | [6e1255aa44](https://linux-hardware.org/?probe=6e1255aa44) | Dec 28, 2022 |
| Lenovo        | IdeaPadFlex 15 20309        | [5cbcee30c7](https://linux-hardware.org/?probe=5cbcee30c7) | Dec 28, 2022 |
| Lenovo        | IdeaPadFlex 15 20309        | [743ed4d93a](https://linux-hardware.org/?probe=743ed4d93a) | Dec 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [819f9be803](https://linux-hardware.org/?probe=819f9be803) | Dec 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [ad4d919e36](https://linux-hardware.org/?probe=ad4d919e36) | Dec 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [eb5e0b8201](https://linux-hardware.org/?probe=eb5e0b8201) | Dec 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [4ea69511df](https://linux-hardware.org/?probe=4ea69511df) | Dec 27, 2022 |
| Acer          | Aspire A515-51G             | [56ceb67978](https://linux-hardware.org/?probe=56ceb67978) | Dec 26, 2022 |
| Acer          | Aspire A515-51G             | [e44b069b44](https://linux-hardware.org/?probe=e44b069b44) | Dec 26, 2022 |
| HP            | Compaq 610                  | [198b4d0586](https://linux-hardware.org/?probe=198b4d0586) | Dec 25, 2022 |
| HP            | Compaq 610                  | [0e9ab46e66](https://linux-hardware.org/?probe=0e9ab46e66) | Dec 25, 2022 |
| ASUSTek       | X550LN                      | [207f82e19c](https://linux-hardware.org/?probe=207f82e19c) | Dec 25, 2022 |
| Dell          | Inspiron N5010              | [389475ec30](https://linux-hardware.org/?probe=389475ec30) | Dec 25, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [81fcc00d18](https://linux-hardware.org/?probe=81fcc00d18) | Dec 24, 2022 |
| Lenovo        | ThinkPad R61 8918DMG        | [d40595761e](https://linux-hardware.org/?probe=d40595761e) | Dec 24, 2022 |
| HP            | Compaq 6730b (NB034ET#UU... | [304e2ca750](https://linux-hardware.org/?probe=304e2ca750) | Dec 24, 2022 |
| Dell          | Latitude 7490               | [d5223c073b](https://linux-hardware.org/?probe=d5223c073b) | Dec 23, 2022 |
| eMachines     | E725                        | [86939210d0](https://linux-hardware.org/?probe=86939210d0) | Dec 22, 2022 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [6db25ba5ca](https://linux-hardware.org/?probe=6db25ba5ca) | Dec 22, 2022 |
| HP            | Laptop 17-ak0xx             | [7e77870894](https://linux-hardware.org/?probe=7e77870894) | Dec 21, 2022 |
| HP            | Laptop 17-ak0xx             | [04c205c943](https://linux-hardware.org/?probe=04c205c943) | Dec 21, 2022 |
| Dell          | Latitude E6230              | [80012cb415](https://linux-hardware.org/?probe=80012cb415) | Dec 19, 2022 |
| Lenovo        | ThinkPad T450 20BUS0QT02    | [439cd38614](https://linux-hardware.org/?probe=439cd38614) | Dec 18, 2022 |
| Acer          | Swift SF114-32              | [757b666913](https://linux-hardware.org/?probe=757b666913) | Dec 18, 2022 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [56e75d70fa](https://linux-hardware.org/?probe=56e75d70fa) | Dec 18, 2022 |
| Dell          | Latitude E6230              | [ba7fa25841](https://linux-hardware.org/?probe=ba7fa25841) | Dec 17, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [a481e4a590](https://linux-hardware.org/?probe=a481e4a590) | Dec 17, 2022 |
| Dell          | Inspiron M5030              | [265739601c](https://linux-hardware.org/?probe=265739601c) | Dec 16, 2022 |
| HP            | Laptop 17-ak0xx             | [0ed9c8a241](https://linux-hardware.org/?probe=0ed9c8a241) | Dec 16, 2022 |
| ASUSTek       | X550LN                      | [d09c34a000](https://linux-hardware.org/?probe=d09c34a000) | Dec 16, 2022 |
| HP            | EliteBook 850 G4            | [0a2fc94b9a](https://linux-hardware.org/?probe=0a2fc94b9a) | Dec 14, 2022 |
| Dell          | Inspiron 14 5401            | [0138a1b2d4](https://linux-hardware.org/?probe=0138a1b2d4) | Dec 13, 2022 |
| Lenovo        | E50-80 80J2                 | [9dc9070ae6](https://linux-hardware.org/?probe=9dc9070ae6) | Dec 13, 2022 |
| Lenovo        | E50-80 80J2                 | [cf9f4d4a79](https://linux-hardware.org/?probe=cf9f4d4a79) | Dec 13, 2022 |
| Acer          | Extensa 5630                | [ec4f446d23](https://linux-hardware.org/?probe=ec4f446d23) | Dec 11, 2022 |
| HP            | 255 G7 Notebook PC          | [b7a944c773](https://linux-hardware.org/?probe=b7a944c773) | Dec 11, 2022 |
| HP            | 650                         | [add4ca69e3](https://linux-hardware.org/?probe=add4ca69e3) | Dec 11, 2022 |
| HP            | 650                         | [9bb3729969](https://linux-hardware.org/?probe=9bb3729969) | Dec 11, 2022 |
| Acer          | TravelMate 8571             | [63aa77ba8d](https://linux-hardware.org/?probe=63aa77ba8d) | Dec 10, 2022 |
| ASUSTek       | K54HR                       | [32870f2fa3](https://linux-hardware.org/?probe=32870f2fa3) | Dec 10, 2022 |
| ASUSTek       | K54HR                       | [fac8091847](https://linux-hardware.org/?probe=fac8091847) | Dec 10, 2022 |
| Dell          | Inspiron 3542               | [eb1d437253](https://linux-hardware.org/?probe=eb1d437253) | Dec 10, 2022 |
| Dell          | Inspiron 13-5378            | [2a7d96e2eb](https://linux-hardware.org/?probe=2a7d96e2eb) | Dec 10, 2022 |
| ASUSTek       | X200MA                      | [1cb00c612b](https://linux-hardware.org/?probe=1cb00c612b) | Dec 09, 2022 |
| HP            | Laptop 15-db0xxx            | [9617825518](https://linux-hardware.org/?probe=9617825518) | Dec 09, 2022 |
| HP            | Laptop 15-db0xxx            | [7b1075fd9b](https://linux-hardware.org/?probe=7b1075fd9b) | Dec 09, 2022 |
| Acer          | TravelMate 8571             | [89270d1f7c](https://linux-hardware.org/?probe=89270d1f7c) | Dec 08, 2022 |
| Acer          | Nitro AN515-51              | [177d3d8e16](https://linux-hardware.org/?probe=177d3d8e16) | Dec 08, 2022 |
| Dell          | Inspiron M5030              | [f73021e3c7](https://linux-hardware.org/?probe=f73021e3c7) | Dec 08, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [ea74cd284c](https://linux-hardware.org/?probe=ea74cd284c) | Dec 08, 2022 |
| ASUSTek       | K54HR                       | [66433bdc5e](https://linux-hardware.org/?probe=66433bdc5e) | Dec 07, 2022 |
| Acer          | TravelMate 8571             | [9e7f0672b2](https://linux-hardware.org/?probe=9e7f0672b2) | Dec 06, 2022 |
| Lenovo        | ThinkPad T470 20HES0E71M    | [85fc801717](https://linux-hardware.org/?probe=85fc801717) | Dec 05, 2022 |
| HP            | EliteBook 840 G6            | [f8e5635371](https://linux-hardware.org/?probe=f8e5635371) | Dec 04, 2022 |
| ASUSTek       | K54HR                       | [264d0d02bb](https://linux-hardware.org/?probe=264d0d02bb) | Dec 04, 2022 |
| Acer          | TravelMate 8571             | [df032cacb6](https://linux-hardware.org/?probe=df032cacb6) | Dec 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [32dbbbf380](https://linux-hardware.org/?probe=32dbbbf380) | Dec 03, 2022 |
| Dell          | Latitude E6220              | [8c99ad2bde](https://linux-hardware.org/?probe=8c99ad2bde) | Dec 02, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [bdc64a5196](https://linux-hardware.org/?probe=bdc64a5196) | Dec 02, 2022 |
| Dell          | Latitude E5520              | [1b3b69b19f](https://linux-hardware.org/?probe=1b3b69b19f) | Nov 28, 2022 |
| Sony          | VPCYB3V1E                   | [8fc84889a5](https://linux-hardware.org/?probe=8fc84889a5) | Nov 28, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [83a97530e1](https://linux-hardware.org/?probe=83a97530e1) | Nov 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [cd9478ab62](https://linux-hardware.org/?probe=cd9478ab62) | Nov 26, 2022 |
| Dell          | Latitude E5520              | [ce72f1c2a9](https://linux-hardware.org/?probe=ce72f1c2a9) | Nov 25, 2022 |
| HP            | 650                         | [15c69c43ca](https://linux-hardware.org/?probe=15c69c43ca) | Nov 24, 2022 |
| Dell          | Latitude E6540              | [5c474a2cdb](https://linux-hardware.org/?probe=5c474a2cdb) | Nov 24, 2022 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [adcb4db30d](https://linux-hardware.org/?probe=adcb4db30d) | Nov 24, 2022 |
| Acer          | Aspire A315-57G             | [93dc021b03](https://linux-hardware.org/?probe=93dc021b03) | Nov 23, 2022 |
| HP            | Compaq 6720s                | [63a0e0161c](https://linux-hardware.org/?probe=63a0e0161c) | Nov 22, 2022 |
| Lenovo        | G580 20150                  | [6e28c07a6c](https://linux-hardware.org/?probe=6e28c07a6c) | Nov 22, 2022 |
| Acer          | Aspire A315-57G             | [fd41589a1a](https://linux-hardware.org/?probe=fd41589a1a) | Nov 22, 2022 |
| Lenovo        | Z50-70 20354                | [4de72c5631](https://linux-hardware.org/?probe=4de72c5631) | Nov 20, 2022 |
| Valve         | Jupiter                     | [dd6f589d44](https://linux-hardware.org/?probe=dd6f589d44) | Nov 20, 2022 |
| HP            | EliteBook 840 G4            | [943027284b](https://linux-hardware.org/?probe=943027284b) | Nov 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [733e52cbdb](https://linux-hardware.org/?probe=733e52cbdb) | Nov 15, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [3e46bbaa1b](https://linux-hardware.org/?probe=3e46bbaa1b) | Nov 15, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [cf97226a28](https://linux-hardware.org/?probe=cf97226a28) | Nov 15, 2022 |
| Lenovo        | ThinkPad T450s 20BW000DH... | [b9913c760a](https://linux-hardware.org/?probe=b9913c760a) | Nov 14, 2022 |
| HP            | Unknown                     | [f76118ac5f](https://linux-hardware.org/?probe=f76118ac5f) | Nov 13, 2022 |
| HP            | Unknown                     | [8cd95516d0](https://linux-hardware.org/?probe=8cd95516d0) | Nov 13, 2022 |
| HP            | 650                         | [100707d1eb](https://linux-hardware.org/?probe=100707d1eb) | Nov 13, 2022 |
| Fujitsu       | LIFEBOOK E752               | [be50b73bfe](https://linux-hardware.org/?probe=be50b73bfe) | Nov 12, 2022 |
| Fujitsu       | LIFEBOOK E752               | [affbec4acb](https://linux-hardware.org/?probe=affbec4acb) | Nov 12, 2022 |
| Lenovo        | Y520-15IKBM 80YY            | [36b3c3d634](https://linux-hardware.org/?probe=36b3c3d634) | Nov 09, 2022 |
| Acer          | Aspire A315-42              | [8f4c16021c](https://linux-hardware.org/?probe=8f4c16021c) | Nov 09, 2022 |
| HP            | 625                         | [2d8090e61e](https://linux-hardware.org/?probe=2d8090e61e) | Nov 08, 2022 |
| Unknown       | Unknown                     | [010a383efa](https://linux-hardware.org/?probe=010a383efa) | Nov 07, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [da41b87b7c](https://linux-hardware.org/?probe=da41b87b7c) | Nov 07, 2022 |
| ASUSTek       | F5V                         | [877e968b61](https://linux-hardware.org/?probe=877e968b61) | Nov 07, 2022 |
| HP            | 650                         | [fd3b93e8fb](https://linux-hardware.org/?probe=fd3b93e8fb) | Nov 05, 2022 |
| Dell          | Latitude 3420               | [f30c035ae6](https://linux-hardware.org/?probe=f30c035ae6) | Nov 05, 2022 |
| Dell          | Latitude E7250              | [0c36cbc6ca](https://linux-hardware.org/?probe=0c36cbc6ca) | Nov 03, 2022 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [c83f37c114](https://linux-hardware.org/?probe=c83f37c114) | Nov 01, 2022 |
| Dell          | G5 5587                     | [a4e32e9eb8](https://linux-hardware.org/?probe=a4e32e9eb8) | Nov 01, 2022 |
| Dell          | Inspiron 5558               | [416655ce7d](https://linux-hardware.org/?probe=416655ce7d) | Oct 30, 2022 |
| Dell          | Inspiron 5558               | [ae71fe1a19](https://linux-hardware.org/?probe=ae71fe1a19) | Oct 30, 2022 |
| Lenovo        | ThinkPad W510 431965U       | [56dd93206a](https://linux-hardware.org/?probe=56dd93206a) | Oct 29, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [aea626acae](https://linux-hardware.org/?probe=aea626acae) | Oct 29, 2022 |
| Dell          | Inspiron 7737               | [f352df76ef](https://linux-hardware.org/?probe=f352df76ef) | Oct 29, 2022 |
| Phoenix/Si... | M7x0S                       | [8b27fc5eb3](https://linux-hardware.org/?probe=8b27fc5eb3) | Oct 29, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HM... | [3b67700f14](https://linux-hardware.org/?probe=3b67700f14) | Oct 28, 2022 |
| HP            | Compaq nx6310 (EY589ES#A... | [a80d2e7626](https://linux-hardware.org/?probe=a80d2e7626) | Oct 27, 2022 |
| Fujitsu       | LIFEBOOK U745               | [7cb792e432](https://linux-hardware.org/?probe=7cb792e432) | Oct 27, 2022 |
| Fujitsu       | LIFEBOOK U745               | [0c33d71210](https://linux-hardware.org/?probe=0c33d71210) | Oct 27, 2022 |
| ASUSTek       | K55VJ                       | [eac363d110](https://linux-hardware.org/?probe=eac363d110) | Oct 25, 2022 |
| ALLDOCUBE     | i1402A                      | [22c255e8cd](https://linux-hardware.org/?probe=22c255e8cd) | Oct 25, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [e5d5599bc7](https://linux-hardware.org/?probe=e5d5599bc7) | Oct 25, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [9cc8a69671](https://linux-hardware.org/?probe=9cc8a69671) | Oct 25, 2022 |
| Dell          | Vostro 3501                 | [df16ec68c3](https://linux-hardware.org/?probe=df16ec68c3) | Oct 24, 2022 |
| Dell          | Vostro 3501                 | [996a5a3b8d](https://linux-hardware.org/?probe=996a5a3b8d) | Oct 24, 2022 |
| HP            | Compaq 6910p (GH717AW#AB... | [02d31506a2](https://linux-hardware.org/?probe=02d31506a2) | Oct 24, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [c24c3f0836](https://linux-hardware.org/?probe=c24c3f0836) | Oct 23, 2022 |
| Dell          | Latitude E6230              | [73ee8be4e9](https://linux-hardware.org/?probe=73ee8be4e9) | Oct 23, 2022 |
| Dell          | Latitude E6230              | [52ee15a8f5](https://linux-hardware.org/?probe=52ee15a8f5) | Oct 23, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [bd25fa1073](https://linux-hardware.org/?probe=bd25fa1073) | Oct 23, 2022 |
| Dell          | Latitude 7390               | [71f8a9e59b](https://linux-hardware.org/?probe=71f8a9e59b) | Oct 22, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [0cf70c348b](https://linux-hardware.org/?probe=0cf70c348b) | Oct 21, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [238c40d2e4](https://linux-hardware.org/?probe=238c40d2e4) | Oct 19, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [680823db07](https://linux-hardware.org/?probe=680823db07) | Oct 19, 2022 |
| Alcor Digi... | Snugbook N1431              | [eb7940e5a4](https://linux-hardware.org/?probe=eb7940e5a4) | Oct 19, 2022 |
| eMachines     | E725                        | [ea21ca2d78](https://linux-hardware.org/?probe=ea21ca2d78) | Oct 19, 2022 |
| Alcor Digi... | Snugbook N1431              | [098e362854](https://linux-hardware.org/?probe=098e362854) | Oct 19, 2022 |
| eMachines     | E725                        | [6d5ddca6c9](https://linux-hardware.org/?probe=6d5ddca6c9) | Oct 18, 2022 |
| Lenovo        | ThinkPad T490 20N2S29E00    | [dd61a6ea26](https://linux-hardware.org/?probe=dd61a6ea26) | Oct 18, 2022 |
| Dell          | Inspiron 3584               | [c80df2b63c](https://linux-hardware.org/?probe=c80df2b63c) | Oct 17, 2022 |
| Acer          | Aspire A717-71G             | [969c0ac771](https://linux-hardware.org/?probe=969c0ac771) | Oct 17, 2022 |
| eMachines     | E725                        | [f365f1eaa7](https://linux-hardware.org/?probe=f365f1eaa7) | Oct 17, 2022 |
| eMachines     | E725                        | [7003528b88](https://linux-hardware.org/?probe=7003528b88) | Oct 17, 2022 |
| ASUSTek       | GL552VW                     | [a49ebeea02](https://linux-hardware.org/?probe=a49ebeea02) | Oct 17, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [528fc3c5ec](https://linux-hardware.org/?probe=528fc3c5ec) | Oct 17, 2022 |
| Unknown       | Unknown                     | [07a141abbb](https://linux-hardware.org/?probe=07a141abbb) | Oct 14, 2022 |
| eMachines     | E725                        | [77e7244d88](https://linux-hardware.org/?probe=77e7244d88) | Oct 14, 2022 |
| eMachines     | E725                        | [34538c32c5](https://linux-hardware.org/?probe=34538c32c5) | Oct 14, 2022 |
| Lenovo        | Z50-75 80EC                 | [b36e579d37](https://linux-hardware.org/?probe=b36e579d37) | Oct 14, 2022 |
| Unknown       | Unknown                     | [0d8c24c367](https://linux-hardware.org/?probe=0d8c24c367) | Oct 13, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [f4d09b3dae](https://linux-hardware.org/?probe=f4d09b3dae) | Oct 13, 2022 |
| Lenovo        | ThinkPad SL510 2847CXG      | [5680d8a827](https://linux-hardware.org/?probe=5680d8a827) | Oct 12, 2022 |
| Acer          | Aspire A515-45              | [3ba623cebe](https://linux-hardware.org/?probe=3ba623cebe) | Oct 12, 2022 |
| Dell          | Latitude 5410               | [e468acae5c](https://linux-hardware.org/?probe=e468acae5c) | Oct 11, 2022 |
| Lenovo        | ThinkPad W530 2463A58       | [dc933df0a9](https://linux-hardware.org/?probe=dc933df0a9) | Oct 10, 2022 |
| ASUSTek       | X550VX                      | [63a8f1baa1](https://linux-hardware.org/?probe=63a8f1baa1) | Oct 10, 2022 |
| ASUSTek       | X550VX                      | [7f9e9ab40b](https://linux-hardware.org/?probe=7f9e9ab40b) | Oct 10, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [5268977f64](https://linux-hardware.org/?probe=5268977f64) | Oct 09, 2022 |
| ASUSTek       | F3Sv                        | [042104bbc2](https://linux-hardware.org/?probe=042104bbc2) | Oct 08, 2022 |
| Lenovo        | V145-15AST 81MT             | [91163f885b](https://linux-hardware.org/?probe=91163f885b) | Oct 07, 2022 |
| Lenovo        | ThinkPad T460s 20FAS30L0... | [ea6a5c970c](https://linux-hardware.org/?probe=ea6a5c970c) | Oct 07, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [7f186dfabd](https://linux-hardware.org/?probe=7f186dfabd) | Oct 07, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [6bae0e4f18](https://linux-hardware.org/?probe=6bae0e4f18) | Oct 07, 2022 |
| eMachines     | E725                        | [9a77e04f3c](https://linux-hardware.org/?probe=9a77e04f3c) | Oct 05, 2022 |
| eMachines     | E725                        | [e413d82fa5](https://linux-hardware.org/?probe=e413d82fa5) | Oct 05, 2022 |
| Dell          | Inspiron 5593               | [33e28ce993](https://linux-hardware.org/?probe=33e28ce993) | Oct 05, 2022 |
| Lenovo        | ThinkPad T410 2537CS0       | [c6a45619c4](https://linux-hardware.org/?probe=c6a45619c4) | Oct 03, 2022 |
| Toshiba       | Satellite M50D-A            | [6eaada1ab0](https://linux-hardware.org/?probe=6eaada1ab0) | Oct 03, 2022 |
| Lenovo        | ThinkPad X230 2325Y5L       | [7c5c62cc90](https://linux-hardware.org/?probe=7c5c62cc90) | Oct 03, 2022 |
| HP            | EliteBook 850 G1            | [7bb0235bd2](https://linux-hardware.org/?probe=7bb0235bd2) | Oct 03, 2022 |
| Dell          | Latitude D630               | [90dc2dddf8](https://linux-hardware.org/?probe=90dc2dddf8) | Oct 02, 2022 |
| Sony          | SVS13118GBB                 | [48dd8fb419](https://linux-hardware.org/?probe=48dd8fb419) | Oct 01, 2022 |
| Dell          | Latitude D630               | [d00c756052](https://linux-hardware.org/?probe=d00c756052) | Oct 01, 2022 |
| Sony          | SVS13118GBB                 | [75e6dbe3d2](https://linux-hardware.org/?probe=75e6dbe3d2) | Oct 01, 2022 |
| ASUSTek       | Strix 15 GL503GE            | [e48bab666f](https://linux-hardware.org/?probe=e48bab666f) | Oct 01, 2022 |
| Sony          | SVS13118GBB                 | [0e0ca26d00](https://linux-hardware.org/?probe=0e0ca26d00) | Sep 30, 2022 |
| Sony          | SVS13118GBB                 | [12868cf90f](https://linux-hardware.org/?probe=12868cf90f) | Sep 30, 2022 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | [1ff8e037f4](https://linux-hardware.org/?probe=1ff8e037f4) | Sep 30, 2022 |
| Acer          | Aspire E5-521               | [a55d68e93c](https://linux-hardware.org/?probe=a55d68e93c) | Sep 30, 2022 |
| Acer          | Aspire A715-72G             | [8b7e129d4a](https://linux-hardware.org/?probe=8b7e129d4a) | Sep 29, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [65f56cc48b](https://linux-hardware.org/?probe=65f56cc48b) | Sep 29, 2022 |
| Lenovo        | IdeaPad 3 15ARE 81W4        | [b784552e84](https://linux-hardware.org/?probe=b784552e84) | Sep 28, 2022 |
| eMachines     | E725                        | [04c9a24d86](https://linux-hardware.org/?probe=04c9a24d86) | Sep 28, 2022 |
| eMachines     | E725                        | [f99f2244c7](https://linux-hardware.org/?probe=f99f2244c7) | Sep 28, 2022 |
| Acer          | Aspire E1-531               | [b7d37d0c6f](https://linux-hardware.org/?probe=b7d37d0c6f) | Sep 27, 2022 |
| Acer          | Aspire E1-531               | [90856d2122](https://linux-hardware.org/?probe=90856d2122) | Sep 27, 2022 |
| ASUSTek       | 1015BX                      | [5190c360db](https://linux-hardware.org/?probe=5190c360db) | Sep 25, 2022 |
| HP            | 650                         | [f835e52a64](https://linux-hardware.org/?probe=f835e52a64) | Sep 25, 2022 |
| HP            | Compaq 6710b (KE125ET#AB... | [fc7831b371](https://linux-hardware.org/?probe=fc7831b371) | Sep 23, 2022 |
| HP            | Compaq 6710b (KE125ET#AB... | [15cffbb03b](https://linux-hardware.org/?probe=15cffbb03b) | Sep 23, 2022 |
| Fujitsu       | LIFEBOOK U745               | [0570d2318c](https://linux-hardware.org/?probe=0570d2318c) | Sep 23, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [4d47a6bfcf](https://linux-hardware.org/?probe=4d47a6bfcf) | Sep 22, 2022 |
| ASUSTek       | K54HR                       | [dbf0f3b1c8](https://linux-hardware.org/?probe=dbf0f3b1c8) | Sep 21, 2022 |
| ASUSTek       | K54HR                       | [25fd2ae90c](https://linux-hardware.org/?probe=25fd2ae90c) | Sep 21, 2022 |
| HP            | 250 G8 Notebook PC          | [17945ad430](https://linux-hardware.org/?probe=17945ad430) | Sep 21, 2022 |
| HP            | 250 G8 Notebook PC          | [49c7f8f204](https://linux-hardware.org/?probe=49c7f8f204) | Sep 21, 2022 |
| Toshiba       | Satellite L450              | [20b85987c4](https://linux-hardware.org/?probe=20b85987c4) | Sep 20, 2022 |
| Toshiba       | Satellite L450              | [9f694612d3](https://linux-hardware.org/?probe=9f694612d3) | Sep 20, 2022 |
| ASUSTek       | X550CL                      | [16d313fefa](https://linux-hardware.org/?probe=16d313fefa) | Sep 20, 2022 |
| eMachines     | E725                        | [141723a3e2](https://linux-hardware.org/?probe=141723a3e2) | Sep 16, 2022 |
| eMachines     | E725                        | [bf27205286](https://linux-hardware.org/?probe=bf27205286) | Sep 15, 2022 |
| Acer          | Aspire 5310                 | [963a5bcade](https://linux-hardware.org/?probe=963a5bcade) | Sep 15, 2022 |
| Dell          | Latitude 7480               | [a9432965f4](https://linux-hardware.org/?probe=a9432965f4) | Sep 15, 2022 |
| Timi          | RedmiBook Pro 15S           | [20b9167fee](https://linux-hardware.org/?probe=20b9167fee) | Sep 11, 2022 |
| HP            | EliteBook 860 16 inch G9... | [080ffe37b9](https://linux-hardware.org/?probe=080ffe37b9) | Sep 08, 2022 |
| Dell          | Latitude E6230              | [41c1130440](https://linux-hardware.org/?probe=41c1130440) | Sep 07, 2022 |
| Dell          | Latitude E6230              | [5e0436a64a](https://linux-hardware.org/?probe=5e0436a64a) | Sep 07, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [32715c6eb9](https://linux-hardware.org/?probe=32715c6eb9) | Sep 06, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [cbc35f08cb](https://linux-hardware.org/?probe=cbc35f08cb) | Sep 06, 2022 |
| Dell          | Latitude 7490               | [4a59725d2d](https://linux-hardware.org/?probe=4a59725d2d) | Sep 05, 2022 |
| Mediacom      | GTZS                        | [d62a43f91e](https://linux-hardware.org/?probe=d62a43f91e) | Sep 04, 2022 |
| HP            | 650                         | [526b86a559](https://linux-hardware.org/?probe=526b86a559) | Sep 04, 2022 |
| HP            | 650                         | [6f184e96df](https://linux-hardware.org/?probe=6f184e96df) | Sep 04, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [e4a4630b4e](https://linux-hardware.org/?probe=e4a4630b4e) | Sep 01, 2022 |
| eMachines     | E725                        | [3e5c01d133](https://linux-hardware.org/?probe=3e5c01d133) | Aug 28, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [1dd156b433](https://linux-hardware.org/?probe=1dd156b433) | Aug 27, 2022 |
| Lenovo        | ThinkPad T420s 4173RT4      | [a10cbdb73b](https://linux-hardware.org/?probe=a10cbdb73b) | Aug 27, 2022 |
| Lenovo        | ThinkPad T420s 4173RT4      | [562d827323](https://linux-hardware.org/?probe=562d827323) | Aug 27, 2022 |
| eMachines     | E725                        | [b73baa0850](https://linux-hardware.org/?probe=b73baa0850) | Aug 25, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [72888e9acb](https://linux-hardware.org/?probe=72888e9acb) | Aug 25, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [92be7f3368](https://linux-hardware.org/?probe=92be7f3368) | Aug 24, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [421ab76c43](https://linux-hardware.org/?probe=421ab76c43) | Aug 24, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Hungary/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| BlackPanther 18.1            | 1076      | 45.5%   |
| Ubuntu 20.04                 | 162       | 6.85%   |
| BlackPanther 16.2            | 159       | 6.72%   |
| Ubuntu 18.04                 | 96        | 4.06%   |
| Ubuntu 22.04                 | 75        | 3.17%   |
| Debian 11                    | 26        | 1.1%    |
| OpenMandriva 4.2             | 21        | 0.89%   |
| Linux Mint 21.1              | 21        | 0.89%   |
| Linux Mint 20.2              | 19        | 0.8%    |
| OpenMandriva 4.3             | 17        | 0.72%   |
| Linux Mint 19.3              | 16        | 0.68%   |
| Fedora 38                    | 16        | 0.68%   |
| ArcoLinux Rolling            | 15        | 0.63%   |
| Zorin 16                     | 13        | 0.55%   |
| Linux Mint 20.3              | 13        | 0.55%   |
| KDE neon 20.04               | 13        | 0.55%   |
| Arch Rolling                 | 13        | 0.55%   |
| Arch                         | 13        | 0.55%   |
| Kubuntu 20.04                | 12        | 0.51%   |
| Ubuntu 21.04                 | 11        | 0.47%   |
| Ubuntu 19.10                 | 11        | 0.47%   |
| Kubuntu 22.04                | 11        | 0.47%   |
| Fedora 37                    | 11        | 0.47%   |
| Ubuntu 21.10                 | 10        | 0.42%   |
| openSUSE Tumbleweed-XXXXXXXX | 10        | 0.42%   |
| Linux Mint 21                | 10        | 0.42%   |
| Fedora 36                    | 10        | 0.42%   |
| Fedora 35                    | 10        | 0.42%   |
| Fedora 33                    | 10        | 0.42%   |
| Ubuntu 19.04                 | 9         | 0.38%   |
| Pop!_OS 22.04                | 9         | 0.38%   |
| Manjaro                      | 9         | 0.38%   |
| Linux Mint 20                | 9         | 0.38%   |
| Endless 3.9.5                | 9         | 0.38%   |
| Debian 10                    | 9         | 0.38%   |
| Xubuntu 18.04                | 8         | 0.34%   |
| Ubuntu 23.04                 | 8         | 0.34%   |
| OpenMandriva 23.03           | 8         | 0.34%   |
| OpenMandriva 23.01           | 8         | 0.34%   |
| Linux Mint 20.1              | 8         | 0.34%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| BlackPanther      | 1216      | 54.07%  |
| Ubuntu            | 378       | 16.81%  |
| Linux Mint        | 98        | 4.36%   |
| Endless           | 74        | 3.29%   |
| Fedora            | 66        | 2.93%   |
| OpenMandriva      | 64        | 2.85%   |
| Debian            | 50        | 2.22%   |
| Manjaro           | 31        | 1.38%   |
| Kubuntu           | 29        | 1.29%   |
| Arch              | 25        | 1.11%   |
| Pop!_OS           | 23        | 1.02%   |
| Xubuntu           | 21        | 0.93%   |
| Zorin             | 19        | 0.84%   |
| KDE neon          | 18        | 0.8%    |
| ArcoLinux         | 17        | 0.76%   |
| openSUSE          | 15        | 0.67%   |
| ROSA              | 12        | 0.53%   |
| Lubuntu           | 9         | 0.4%    |
| Kali              | 9         | 0.4%    |
| Elementary        | 9         | 0.4%    |
| Ubuntu Unity      | 8         | 0.36%   |
| Ubuntu MATE       | 5         | 0.22%   |
| Ubuntu Budgie     | 5         | 0.22%   |
| SteamOS           | 5         | 0.22%   |
| Gentoo            | 4         | 0.18%   |
| Xero              | 3         | 0.13%   |
| EndeavourOS       | 3         | 0.13%   |
| Clear Linux       | 3         | 0.13%   |
| UbuntuDDE         | 2         | 0.09%   |
| Rocky Linux       | 2         | 0.09%   |
| Q4OS              | 2         | 0.09%   |
| MX                | 2         | 0.09%   |
| LMDE              | 2         | 0.09%   |
| Devuan            | 2         | 0.09%   |
| antiX             | 2         | 0.09%   |
| UHU               | 1         | 0.04%   |
| Ubuntu Studio     | 1         | 0.04%   |
| Solus             | 1         | 0.04%   |
| Slackware-current | 1         | 0.04%   |
| PCLinuxOS         | 1         | 0.04%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 4.18.16-desktop-1bP      | 791       | 30.13%  |
| 5.6.14-desktop-2bP       | 345       | 13.14%  |
| 4.9.20-desktop-pae-1bP   | 150       | 5.71%   |
| 5.1.15-desktop-1bP       | 57        | 2.17%   |
| 5.4.0-42-generic         | 28        | 1.07%   |
| 5.15.85-desktop-1bP      | 28        | 1.07%   |
| 5.8.0-14-generic         | 23        | 0.88%   |
| 5.10.14-desktop-1omv4002 | 20        | 0.76%   |
| 5.16.7-desktop-1omv4003  | 16        | 0.61%   |
| 5.4.0-58-generic         | 14        | 0.53%   |
| 4.18.0-15-generic        | 14        | 0.53%   |
| 5.3.0-28-generic         | 12        | 0.46%   |
| 5.15.0-43-generic        | 12        | 0.46%   |
| 5.4.0-52-generic         | 11        | 0.42%   |
| 5.4.0-48-generic         | 11        | 0.42%   |
| 5.4.0-19-generic         | 11        | 0.42%   |
| 5.15.0-52-generic        | 11        | 0.42%   |
| 5.11.0-27-generic        | 11        | 0.42%   |
| 5.4.0-40-generic         | 9         | 0.34%   |
| 5.4.0-29-generic         | 9         | 0.34%   |
| 5.15.0-58-generic        | 9         | 0.34%   |
| 5.15.0-41-generic        | 9         | 0.34%   |
| 5.11.0-34-generic        | 9         | 0.34%   |
| 6.1.1-desktop-1omv2290   | 8         | 0.3%    |
| 5.19.0-35-generic        | 8         | 0.3%    |
| 6.2.6-desktop-1omv2390   | 7         | 0.27%   |
| 5.4.0-54-generic         | 7         | 0.27%   |
| 5.4.0-26-generic         | 7         | 0.27%   |
| 5.15.0-76-generic        | 7         | 0.27%   |
| 5.15.0-46-generic        | 7         | 0.27%   |
| 5.8.0-53-generic         | 6         | 0.23%   |
| 5.4.0-91-generic         | 6         | 0.23%   |
| 5.4.0-81-generic         | 6         | 0.23%   |
| 5.4.0-39-generic         | 6         | 0.23%   |
| 5.3.0-23-generic         | 6         | 0.23%   |
| 5.15.0-67-generic        | 6         | 0.23%   |
| 5.15.0-56-generic        | 6         | 0.23%   |
| 5.15.0-53-generic        | 6         | 0.23%   |
| 5.15.0-50-generic        | 6         | 0.23%   |
| 5.15.0-48-generic        | 6         | 0.23%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18.16 | 791       | 31.09%  |
| 5.6.14  | 346       | 13.6%   |
| 5.4.0   | 200       | 7.86%   |
| 4.9.20  | 158       | 6.21%   |
| 5.15.0  | 120       | 4.72%   |
| 4.15.0  | 69        | 2.71%   |
| 5.8.0   | 61        | 2.4%    |
| 5.1.15  | 57        | 2.24%   |
| 5.11.0  | 56        | 2.2%    |
| 5.3.0   | 51        | 2%      |
| 5.13.0  | 49        | 1.93%   |
| 5.10.0  | 40        | 1.57%   |
| 5.19.0  | 33        | 1.3%    |
| 5.0.0   | 33        | 1.3%    |
| 4.18.0  | 31        | 1.22%   |
| 5.15.85 | 29        | 1.14%   |
| 5.10.14 | 20        | 0.79%   |
| 6.2.0   | 17        | 0.67%   |
| 5.16.7  | 17        | 0.67%   |
| 6.1.0   | 11        | 0.43%   |
| 6.2.6   | 10        | 0.39%   |
| 6.1.1   | 10        | 0.39%   |
| 4.19.0  | 9         | 0.35%   |
| 4.13.0  | 8         | 0.31%   |
| 6.3.8   | 7         | 0.28%   |
| 6.2.9   | 7         | 0.28%   |
| 5.9.0   | 6         | 0.24%   |
| 5.14.0  | 6         | 0.24%   |
| 4.4.0   | 6         | 0.24%   |
| 6.4.11  | 5         | 0.2%    |
| 5.16.0  | 5         | 0.2%    |
| 6.4.3   | 4         | 0.16%   |
| 6.3.5   | 4         | 0.16%   |
| 6.2.14  | 4         | 0.16%   |
| 5.15.12 | 4         | 0.16%   |
| 5.12.9  | 4         | 0.16%   |
| 5.12.4  | 4         | 0.16%   |
| 5.10.7  | 4         | 0.16%   |
| 4.16.0  | 4         | 0.16%   |
| 6.4.7   | 3         | 0.12%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18    | 821       | 32.46%  |
| 5.6     | 356       | 14.08%  |
| 5.4     | 212       | 8.38%   |
| 5.15    | 167       | 6.6%    |
| 4.9     | 166       | 6.56%   |
| 5.10    | 73        | 2.89%   |
| 5.8     | 71        | 2.81%   |
| 4.15    | 69        | 2.73%   |
| 5.11    | 66        | 2.61%   |
| 5.1     | 57        | 2.25%   |
| 5.3     | 56        | 2.21%   |
| 5.13    | 53        | 2.1%    |
| 6.2     | 44        | 1.74%   |
| 5.19    | 42        | 1.66%   |
| 6.1     | 40        | 1.58%   |
| 5.16    | 35        | 1.38%   |
| 5.0     | 33        | 1.3%    |
| 6.4     | 25        | 0.99%   |
| 6.3     | 20        | 0.79%   |
| 5.12    | 15        | 0.59%   |
| 5.14    | 14        | 0.55%   |
| 5.9     | 13        | 0.51%   |
| 6.0     | 12        | 0.47%   |
| 5.18    | 12        | 0.47%   |
| 4.19    | 10        | 0.4%    |
| 5.17    | 9         | 0.36%   |
| 4.13    | 8         | 0.32%   |
| 5.7     | 7         | 0.28%   |
| 4.4     | 6         | 0.24%   |
| 5.5     | 4         | 0.16%   |
| 4.16    | 4         | 0.16%   |
| 6.5     | 3         | 0.12%   |
| 4.7     | 2         | 0.08%   |
| 5.2     | 1         | 0.04%   |
| 4.14    | 1         | 0.04%   |
| 4.1     | 1         | 0.04%   |
| 3.16    | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 1998      | 90.98%  |
| i686   | 198       | 9.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KDE5            | 1347      | 59.79%  |
| GNOME           | 461       | 20.46%  |
| Unknown         | 157       | 6.97%   |
| X-Cinnamon      | 78        | 3.46%   |
| XFCE            | 73        | 3.24%   |
| MATE            | 32        | 1.42%   |
| KDE             | 26        | 1.15%   |
| Cinnamon        | 19        | 0.84%   |
| LXQt            | 10        | 0.44%   |
| Pantheon        | 9         | 0.4%    |
| KDE4            | 9         | 0.4%    |
| Unity           | 8         | 0.36%   |
| Budgie          | 6         | 0.27%   |
| GNOME Flashback | 4         | 0.18%   |
| Deepin          | 4         | 0.18%   |
| i3              | 3         | 0.13%   |
| LXDE            | 2         | 0.09%   |
| qtile           | 1         | 0.04%   |
| ICEWM           | 1         | 0.04%   |
| GNOME Classic   | 1         | 0.04%   |
| bspwm           | 1         | 0.04%   |
| awesome         | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 1947      | 87.66%  |
| Wayland | 176       | 7.92%   |
| Unknown | 91        | 4.1%    |
| Tty     | 7         | 0.32%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 1348      | 60.07%  |
| Unknown | 494       | 22.01%  |
| GDM3    | 123       | 5.48%   |
| GDM     | 122       | 5.44%   |
| LightDM | 109       | 4.86%   |
| TDM     | 34        | 1.52%   |
| KDM     | 9         | 0.4%    |
| SLiM    | 3         | 0.13%   |
| XDM     | 2         | 0.09%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1331      | 59.47%  |
| hu_HU   | 538       | 24.04%  |
| en_US   | 292       | 13.05%  |
| en_GB   | 31        | 1.39%   |
| C       | 18        | 0.8%    |
| de_DE   | 9         | 0.4%    |
| ru_UA   | 3         | 0.13%   |
| en_AU   | 3         | 0.13%   |
| ru_RU   | 2         | 0.09%   |
| POSIX   | 2         | 0.09%   |
| nl_NL   | 2         | 0.09%   |
| it_IT   | 1         | 0.04%   |
| fr_BE   | 1         | 0.04%   |
| en_ZA   | 1         | 0.04%   |
| en_IN   | 1         | 0.04%   |
| en_IL   | 1         | 0.04%   |
| de_AT   | 1         | 0.04%   |
| C.UTF8  | 1         | 0.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 1301      | 57.29%  |
| EFI  | 970       | 42.71%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 1334      | 55.84%  |
| Overlay | 858       | 35.91%  |
| Btrfs   | 86        | 3.6%    |
| Unknown | 60        | 2.51%   |
| Tmpfs   | 22        | 0.92%   |
| Xfs     | 9         | 0.38%   |
| Ext3    | 6         | 0.25%   |
| Ext2    | 6         | 0.25%   |
| Zfs     | 5         | 0.21%   |
| F2fs    | 2         | 0.08%   |
| XXXXXXX | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| MBR     | 966       | 42.18%  |
| GPT     | 801       | 34.98%  |
| Unknown | 523       | 22.84%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1814      | 77.52%  |
| Yes       | 526       | 22.48%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1355      | 58.66%  |
| Yes       | 955       | 41.34%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 458       | 21.1%   |
| Hewlett-Packard     | 418       | 19.25%  |
| Dell                | 379       | 17.46%  |
| ASUSTek Computer    | 316       | 14.56%  |
| Acer                | 237       | 10.92%  |
| Toshiba             | 58        | 2.67%   |
| Samsung Electronics | 38        | 1.75%   |
| Fujitsu Siemens     | 36        | 1.66%   |
| Fujitsu             | 33        | 1.52%   |
| Packard Bell        | 30        | 1.38%   |
| eMachines           | 21        | 0.97%   |
| MSI                 | 20        | 0.92%   |
| Sony                | 17        | 0.78%   |
| Medion              | 14        | 0.64%   |
| Apple               | 13        | 0.6%    |
| Alcor               | 8         | 0.37%   |
| Hungaro Flotta Kft  | 7         | 0.32%   |
| HUAWEI              | 6         | 0.28%   |
| Unknown             | 6         | 0.28%   |
| Valve               | 5         | 0.23%   |
| Insyde              | 4         | 0.18%   |
| Timi                | 3         | 0.14%   |
| Intel               | 3         | 0.14%   |
| Gigabyte Technology | 3         | 0.14%   |
| Clevo               | 3         | 0.14%   |
| TUXEDO              | 2         | 0.09%   |
| speedmaster         | 2         | 0.09%   |
| Panasonic           | 2         | 0.09%   |
| Notebook            | 2         | 0.09%   |
| Mediacom            | 2         | 0.09%   |
| LG Electronics      | 2         | 0.09%   |
| Google              | 2         | 0.09%   |
| Zebra Technologies  | 1         | 0.05%   |
| UMAX                | 1         | 0.05%   |
| THD                 | 1         | 0.05%   |
| TCL Communication   | 1         | 0.05%   |
| RM                  | 1         | 0.05%   |
| Phoenix/SiS         | 1         | 0.05%   |
| ordissimo           | 1         | 0.05%   |
| NEC Computers       | 1         | 0.05%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| HP 250 G1                            | 41        | 1.89%   |
| Dell Latitude E6410                  | 19        | 0.88%   |
| Unknown                              | 15        | 0.69%   |
| HP Notebook                          | 13        | 0.6%    |
| HP 650                               | 13        | 0.6%    |
| Lenovo IdeaPad 330-15IKB 81DE        | 11        | 0.51%   |
| Lenovo IdeaPad 100-15IBD 80QQ        | 11        | 0.51%   |
| Lenovo G50-45 80E3                   | 11        | 0.51%   |
| HP 620                               | 10        | 0.46%   |
| Dell Latitude E6400                  | 10        | 0.46%   |
| Lenovo ThinkPad T400 2768WGB         | 9         | 0.41%   |
| HP Pavilion 15                       | 8         | 0.37%   |
| HP EliteBook 8460p                   | 8         | 0.37%   |
| Dell Latitude E6530                  | 8         | 0.37%   |
| Dell Latitude E6420                  | 8         | 0.37%   |
| Dell Inspiron 15-3567                | 8         | 0.37%   |
| ASUS X541NA                          | 8         | 0.37%   |
| Lenovo Z50-75 80EC                   | 7         | 0.32%   |
| Lenovo G580 20150                    | 7         | 0.32%   |
| Lenovo G550 20023                    | 7         | 0.32%   |
| HP EliteBook 6930p                   | 7         | 0.32%   |
| Dell Latitude E6430                  | 7         | 0.32%   |
| Dell Inspiron 3542                   | 7         | 0.32%   |
| ASUS VivoBook 15_ASUS Laptop X540UBR | 7         | 0.32%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR | 7         | 0.32%   |
| Lenovo Z50-70 20354                  | 6         | 0.28%   |
| Lenovo IdeaPad 100-15IBY 80MJ        | 6         | 0.28%   |
| HP Pavilion g6                       | 6         | 0.28%   |
| HP EliteBook 8470p                   | 6         | 0.28%   |
| HP EliteBook 8440p                   | 6         | 0.28%   |
| HP EliteBook 2560p                   | 6         | 0.28%   |
| HP 250 G6 Notebook PC                | 6         | 0.28%   |
| eMachines E725                       | 6         | 0.28%   |
| eMachines E525                       | 6         | 0.28%   |
| Dell Vostro 15-3568                  | 6         | 0.28%   |
| Dell Latitude E7450                  | 6         | 0.28%   |
| Dell Latitude E5420                  | 6         | 0.28%   |
| Dell Latitude D630                   | 6         | 0.28%   |
| Dell Latitude 5480                   | 6         | 0.28%   |
| Dell Inspiron N5110                  | 6         | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 202       | 9.3%    |
| Dell Latitude           | 188       | 8.66%   |
| Acer Aspire             | 168       | 7.74%   |
| Dell Inspiron           | 121       | 5.57%   |
| Lenovo IdeaPad          | 114       | 5.25%   |
| HP EliteBook            | 91        | 4.19%   |
| ASUS VivoBook           | 67        | 3.09%   |
| HP 250                  | 63        | 2.9%    |
| HP ProBook              | 59        | 2.72%   |
| Toshiba Satellite       | 52        | 2.4%    |
| HP Pavilion             | 43        | 1.98%   |
| HP Compaq               | 38        | 1.75%   |
| Dell Vostro             | 32        | 1.47%   |
| Packard Bell EasyNote   | 30        | 1.38%   |
| Fujitsu LIFEBOOK        | 30        | 1.38%   |
| Fujitsu Siemens AMILO   | 21        | 0.97%   |
| Acer TravelMate         | 21        | 0.97%   |
| HP Laptop               | 18        | 0.83%   |
| Acer Swift              | 16        | 0.74%   |
| Unknown                 | 15        | 0.69%   |
| HP Notebook             | 13        | 0.6%    |
| HP 650                  | 13        | 0.6%    |
| ASUS ROG                | 13        | 0.6%    |
| ASUS ASUS               | 13        | 0.6%    |
| Dell Precision          | 12        | 0.55%   |
| Lenovo G50-45           | 11        | 0.51%   |
| HP ZBook                | 11        | 0.51%   |
| HP 620                  | 10        | 0.46%   |
| ASUS ZenBook            | 10        | 0.46%   |
| Lenovo G580             | 9         | 0.41%   |
| Lenovo 3000             | 9         | 0.41%   |
| HP 255                  | 9         | 0.41%   |
| Fujitsu Siemens ESPRIMO | 9         | 0.41%   |
| Lenovo Yoga             | 8         | 0.37%   |
| Lenovo ThinkBook        | 8         | 0.37%   |
| HP Presario             | 8         | 0.37%   |
| ASUS X541NA             | 8         | 0.37%   |
| Acer Extensa            | 8         | 0.37%   |
| Lenovo Z50-75           | 7         | 0.32%   |
| Lenovo G550             | 7         | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 218       | 10.04%  |
| 2013    | 191       | 8.8%    |
| 2010    | 189       | 8.71%   |
| 2018    | 172       | 7.92%   |
| 2012    | 154       | 7.09%   |
| 2014    | 144       | 6.63%   |
| 2015    | 137       | 6.31%   |
| 2017    | 135       | 6.22%   |
| 2008    | 135       | 6.22%   |
| 2016    | 134       | 6.17%   |
| 2009    | 124       | 5.71%   |
| 2019    | 103       | 4.74%   |
| 2007    | 99        | 4.56%   |
| 2020    | 81        | 3.73%   |
| 2021    | 65        | 2.99%   |
| 2006    | 38        | 1.75%   |
| 2022    | 34        | 1.57%   |
| 2005    | 11        | 0.51%   |
| 2023    | 4         | 0.18%   |
| Unknown | 3         | 0.14%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 2171      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 2073      | 94.92%  |
| Enabled  | 111       | 5.08%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2169      | 99.91%  |
| Yes  | 2         | 0.09%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 752       | 33.54%  |
| 4.01-8.0    | 555       | 24.75%  |
| 8.01-16.0   | 289       | 12.89%  |
| 1.01-2.0    | 249       | 11.11%  |
| 16.01-24.0  | 175       | 7.81%   |
| 2.01-3.0    | 95        | 4.24%   |
| 32.01-64.0  | 76        | 3.39%   |
| 0.51-1.0    | 31        | 1.38%   |
| 24.01-32.0  | 16        | 0.71%   |
| 64.01-256.0 | 2         | 0.09%   |
| 0.01-0.5    | 1         | 0.04%   |
| Unknown     | 1         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.51-1.0   | 850       | 33.09%  |
| 1.01-2.0   | 839       | 32.66%  |
| 2.01-3.0   | 321       | 12.5%   |
| 0.01-0.5   | 195       | 7.59%   |
| 3.01-4.0   | 157       | 6.11%   |
| 4.01-8.0   | 155       | 6.03%   |
| 8.01-16.0  | 46        | 1.79%   |
| 16.01-24.0 | 4         | 0.16%   |
| 32.01-64.0 | 1         | 0.04%   |
| Unknown    | 1         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1756      | 77.63%  |
| 2      | 434       | 19.19%  |
| 3      | 45        | 1.99%   |
| 0      | 21        | 0.93%   |
| 4      | 5         | 0.22%   |
| 5      | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1169      | 53.21%  |
| No        | 1028      | 46.79%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1948      | 89.48%  |
| No        | 229       | 10.52%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2139      | 98.48%  |
| No        | 33        | 1.52%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1633      | 74.09%  |
| No        | 571       | 25.91%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Hungary | 2171      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Budapest          | 918       | 35.65%  |
| Debrecen          | 53        | 2.06%   |
| Szeged            | 52        | 2.02%   |
| Pécs             | 52        | 2.02%   |
| Miskolc           | 52        | 2.02%   |
| Tatabánya        | 49        | 1.9%    |
| Győr             | 41        | 1.59%   |
| Székesfehérvár | 35        | 1.36%   |
| Veszprém         | 33        | 1.28%   |
| Szombathely       | 33        | 1.28%   |
| Kecskemét        | 28        | 1.09%   |
| Nyiregyhaza       | 27        | 1.05%   |
| Zalaegerszeg      | 26        | 1.01%   |
| Szigetszentmiklos | 26        | 1.01%   |
| Szolnok           | 25        | 0.97%   |
| Érd              | 23        | 0.89%   |
| Szekszárd        | 18        | 0.7%    |
| Dunaújváros     | 18        | 0.7%    |
| Toekoel           | 16        | 0.62%   |
| Salgotarjan       | 15        | 0.58%   |
| Pomaz             | 14        | 0.54%   |
| Toeroekbalint     | 12        | 0.47%   |
| Szorgalmatos      | 12        | 0.47%   |
| Sopron            | 12        | 0.47%   |
| Kazincbarcika     | 12        | 0.47%   |
| Gödöllő        | 12        | 0.47%   |
| Cegled            | 12        | 0.47%   |
| Nagykanizsa       | 11        | 0.43%   |
| Monor             | 11        | 0.43%   |
| Kaposvár         | 11        | 0.43%   |
| Hatvan            | 11        | 0.43%   |
| Gyomro            | 11        | 0.43%   |
| Maglod            | 10        | 0.39%   |
| Kiskunfelegyhaza  | 10        | 0.39%   |
| Karcag            | 10        | 0.39%   |
| Ajka              | 10        | 0.39%   |
| Tiszaujvaros      | 9         | 0.35%   |
| Tata              | 9         | 0.35%   |
| Solymar           | 9         | 0.35%   |
| Siófok           | 9         | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 390       | 592    | 14.36%  |
| WDC                         | 349       | 506    | 12.85%  |
| Samsung Electronics         | 319       | 495    | 11.75%  |
| Kingston                    | 294       | 442    | 10.83%  |
| Toshiba                     | 262       | 392    | 9.65%   |
| Hitachi                     | 143       | 201    | 5.27%   |
| HGST                        | 139       | 204    | 5.12%   |
| Unknown                     | 105       | 151    | 3.87%   |
| SanDisk                     | 101       | 160    | 3.72%   |
| SK hynix                    | 80        | 114    | 2.95%   |
| Intel                       | 67        | 98     | 2.47%   |
| Micron Technology           | 47        | 67     | 1.73%   |
| Fujitsu                     | 44        | 58     | 1.62%   |
| Crucial                     | 38        | 59     | 1.4%    |
| A-DATA Technology           | 34        | 47     | 1.25%   |
| SPCC                        | 26        | 35     | 0.96%   |
| Apacer                      | 23        | 37     | 0.85%   |
| JMicron Technology          | 18        | 19     | 0.66%   |
| LITEON                      | 16        | 18     | 0.59%   |
| KIOXIA                      | 13        | 17     | 0.48%   |
| Intenso                     | 13        | 27     | 0.48%   |
| China                       | 12        | 25     | 0.44%   |
| PNY                         | 11        | 17     | 0.41%   |
| Kingston Technology Company | 11        | 11     | 0.41%   |
| Kingmax                     | 10        | 10     | 0.37%   |
| LITEONIT                    | 9         | 13     | 0.33%   |
| Patriot                     | 8         | 11     | 0.29%   |
| Gigabyte Technology         | 8         | 11     | 0.29%   |
| Apple                       | 8         | 13     | 0.29%   |
| Transcend                   | 7         | 7      | 0.26%   |
| KingSpec                    | 7         | 8      | 0.26%   |
| OCZ                         | 6         | 6      | 0.22%   |
| Verbatim                    | 5         | 13     | 0.18%   |
| Team                        | 5         | 9      | 0.18%   |
| Silicon Motion              | 5         | 6      | 0.18%   |
| Phison                      | 5         | 6      | 0.18%   |
| GOODRAM                     | 5         | 6      | 0.18%   |
| ASMT                        | 5         | 7      | 0.18%   |
| Unknown                     | 5         | 8      | 0.18%   |
| SSSTC                       | 3         | 10     | 0.11%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD    | 61        | 2.17%   |
| Seagate ST1000LM035-1RK172 1TB     | 58        | 2.06%   |
| Kingston SA400S37120G 120GB SSD    | 56        | 1.99%   |
| Toshiba MQ01ABF050 500GB           | 48        | 1.71%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 43        | 1.53%   |
| Kingston SA400S37480G 480GB SSD    | 40        | 1.42%   |
| Toshiba MQ01ABD100 1TB             | 39        | 1.39%   |
| Seagate ST500LT012-1DG142 500GB    | 36        | 1.28%   |
| Kingston SV300S37A120G 120GB SSD   | 33        | 1.17%   |
| HGST HTS545032A7E380 320GB         | 33        | 1.17%   |
| Toshiba MQ04ABF100 1TB             | 25        | 0.89%   |
| HGST HTS545050A7E680 500GB         | 25        | 0.89%   |
| Samsung SSD 850 EVO 250GB          | 23        | 0.82%   |
| Seagate ST9320325AS 320GB          | 22        | 0.78%   |
| HGST HTS721010A9E630 1TB           | 20        | 0.71%   |
| Seagate ST9500325AS 500GB          | 17        | 0.6%    |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 16        | 0.57%   |
| Samsung SSD 860 EVO 500GB          | 16        | 0.57%   |
| HGST HTS541010A9E680 1TB           | 16        | 0.57%   |
| Seagate ST9250315AS 250GB          | 15        | 0.53%   |
| Kingston SUV400S37120G 120GB SSD   | 15        | 0.53%   |
| WDC WD10JPVX-22JC3T0 1TB           | 13        | 0.46%   |
| WDC WD1600BEVT-22ZCT0 160GB        | 12        | 0.43%   |
| Unknown MMC Card  32GB             | 12        | 0.43%   |
| Seagate ST500LT012-9WS142 500GB    | 12        | 0.43%   |
| HGST HTS725050A7E630 500GB         | 12        | 0.43%   |
| WDC WD5000LPCX-24VHAT0 500GB       | 11        | 0.39%   |
| Seagate M3 Portable 1TB            | 11        | 0.39%   |
| SanDisk NVMe SSD Drive 512GB       | 11        | 0.39%   |
| Samsung NVMe SSD Drive 512GB       | 11        | 0.39%   |
| WDC WD5000LPCX-24C6HT0 500GB       | 10        | 0.36%   |
| WDC WD10SPZX-21Z10T0 1TB           | 10        | 0.36%   |
| WDC WD10JPVX-60JC3T0 1TB           | 10        | 0.36%   |
| SPCC Solid State Disk 128GB        | 10        | 0.36%   |
| JMicron Generic 240GB              | 10        | 0.36%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 9         | 0.32%   |
| WDC WD10SPZX-24Z10 1TB             | 9         | 0.32%   |
| WDC WD10SPCX-24HWST1 1TB           | 9         | 0.32%   |
| Toshiba MQ01ABD050 500GB           | 9         | 0.32%   |
| Samsung SSD 850 EVO 500GB          | 9         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 380       | 575    | 30.21%  |
| WDC                 | 286       | 411    | 22.73%  |
| Toshiba             | 217       | 310    | 17.25%  |
| Hitachi             | 143       | 201    | 11.37%  |
| HGST                | 139       | 204    | 11.05%  |
| Fujitsu             | 44        | 58     | 3.5%    |
| Samsung Electronics | 32        | 39     | 2.54%   |
| Unknown             | 6         | 8      | 0.48%   |
| IBM/Hitachi         | 3         | 4      | 0.24%   |
| Initio              | 2         | 3      | 0.16%   |
| HGST HTS            | 2         | 7      | 0.16%   |
| Space ke            | 1         | 1      | 0.08%   |
| JMicron Technology  | 1         | 1      | 0.08%   |
| CSD                 | 1         | 2      | 0.08%   |
| ASMedia             | 1         | 1      | 0.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 266       | 401    | 28.06%  |
| Samsung Electronics | 178       | 282    | 18.78%  |
| SanDisk             | 64        | 101    | 6.75%   |
| Intel               | 42        | 64     | 4.43%   |
| WDC                 | 39        | 61     | 4.11%   |
| Crucial             | 36        | 57     | 3.8%    |
| SK hynix            | 34        | 54     | 3.59%   |
| A-DATA Technology   | 32        | 45     | 3.38%   |
| Micron Technology   | 31        | 45     | 3.27%   |
| SPCC                | 24        | 33     | 2.53%   |
| Apacer              | 21        | 35     | 2.22%   |
| Toshiba             | 16        | 30     | 1.69%   |
| LITEON              | 15        | 17     | 1.58%   |
| Intenso             | 13        | 27     | 1.37%   |
| China               | 12        | 25     | 1.27%   |
| PNY                 | 11        | 17     | 1.16%   |
| Kingmax             | 10        | 10     | 1.05%   |
| JMicron Technology  | 10        | 10     | 1.05%   |
| LITEONIT            | 9         | 13     | 0.95%   |
| Transcend           | 7         | 7      | 0.74%   |
| Gigabyte Technology | 7         | 10     | 0.74%   |
| Patriot             | 6         | 7      | 0.63%   |
| OCZ                 | 6         | 6      | 0.63%   |
| KingSpec            | 6         | 7      | 0.63%   |
| Verbatim            | 5         | 13     | 0.53%   |
| GOODRAM             | 5         | 6      | 0.53%   |
| Apple               | 5         | 9      | 0.53%   |
| Team                | 4         | 8      | 0.42%   |
| ASMT                | 4         | 6      | 0.42%   |
| Corsair             | 3         | 4      | 0.32%   |
| BHT                 | 3         | 3      | 0.32%   |
| Unknown             | 2         | 4      | 0.21%   |
| Union Memory        | 2         | 6      | 0.21%   |
| Indilinx            | 2         | 2      | 0.21%   |
| HS-SSD-C100         | 2         | 2      | 0.21%   |
| Zheino              | 1         | 1      | 0.11%   |
| TO Exter            | 1         | 1      | 0.11%   |
| Solid               | 1         | 6      | 0.11%   |
| ShiJi               | 1         | 1      | 0.11%   |
| Seagate             | 1         | 1      | 0.11%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1202      | 1825   | 46.7%   |
| SSD     | 876       | 1451   | 34.03%  |
| NVMe    | 356       | 549    | 13.83%  |
| MMC     | 111       | 164    | 4.31%   |
| Unknown | 29        | 34     | 1.13%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1839      | 3196   | 77.17%  |
| NVMe | 356       | 549    | 14.94%  |
| MMC  | 111       | 164    | 4.66%   |
| SAS  | 77        | 114    | 3.23%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1547      | 2550   | 77.04%  |
| 0.51-1.0   | 424       | 672    | 21.12%  |
| 1.01-2.0   | 28        | 43     | 1.39%   |
| 4.01-10.0  | 4         | 4      | 0.2%    |
| 2.01-3.0   | 3         | 5      | 0.15%   |
| 3.01-4.0   | 1         | 1      | 0.05%   |
| 10.01-20.0 | 1         | 1      | 0.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 783       | 31%     |
| 101-250        | 615       | 24.35%  |
| 251-500        | 422       | 16.71%  |
| 51-100         | 189       | 7.48%   |
| 501-1000       | 187       | 7.4%    |
| 1-20           | 114       | 4.51%   |
| 21-50          | 97        | 3.84%   |
| 1001-2000      | 82        | 3.25%   |
| 2001-3000      | 23        | 0.91%   |
| More than 3000 | 14        | 0.55%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 945       | 36.57%  |
| Unknown        | 783       | 30.3%   |
| 21-50          | 283       | 10.95%  |
| 51-100         | 211       | 8.17%   |
| 101-250        | 181       | 7%      |
| 251-500        | 89        | 3.44%   |
| 501-1000       | 58        | 2.24%   |
| 1001-2000      | 29        | 1.12%   |
| 2001-3000      | 3         | 0.12%   |
| More than 3000 | 2         | 0.08%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Notebooks | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| HGST HTS545032A7E380 320GB              | 31        | 48     | 6.21%   |
| HGST HTS545050A7E680 500GB              | 18        | 27     | 3.61%   |
| Toshiba MQ01ABF050 500GB                | 11        | 28     | 2.2%    |
| Seagate ST9320325AS 320GB               | 11        | 23     | 2.2%    |
| Seagate ST500LT012-1DG142 500GB         | 11        | 15     | 2.2%    |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 9         | 13     | 1.8%    |
| Seagate ST500LT012-9WS142 500GB         | 8         | 9      | 1.6%    |
| Toshiba MQ01ABD100 1TB                  | 7         | 9      | 1.4%    |
| Seagate ST9500325AS 500GB               | 7         | 14     | 1.4%    |
| Seagate ST9320423AS 320GB               | 7         | 7      | 1.4%    |
| Seagate ST9250315AS 250GB               | 7         | 9      | 1.4%    |
| Kingston SV300S37A120G 120GB SSD        | 7         | 11     | 1.4%    |
| Samsung Electronics HM160HI 160GB       | 6         | 7      | 1.2%    |
| Hitachi HTS545016B9A300 160GB           | 6         | 6      | 1.2%    |
| HGST HTS541010A9E680 1TB                | 6         | 16     | 1.2%    |
| Toshiba MQ01ABD050 500GB                | 5         | 5      | 1%      |
| Hitachi HTS547550A9E384 500GB           | 5         | 19     | 1%      |
| Hitachi HTS545032B9A300 320GB           | 5         | 6      | 1%      |
| HGST HTS545050A7E380 500GB              | 5         | 9      | 1%      |
| WDC WD10JPVX-22JC3T0 1TB                | 4         | 7      | 0.8%    |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD | 4         | 7      | 0.8%    |
| Seagate ST500LM000-SSHD-8GB             | 4         | 5      | 0.8%    |
| Seagate ST320LT007-9ZV142 320GB         | 4         | 4      | 0.8%    |
| Seagate ST1000LX015-1U7172 1TB          | 4         | 12     | 0.8%    |
| Seagate ST1000LM035-1RK172 1TB          | 4         | 5      | 0.8%    |
| Hitachi HTS723232A7A364 320GB           | 4         | 4      | 0.8%    |
| Hitachi HTS545050B9A300 500GB           | 4         | 6      | 0.8%    |
| Hitachi HTS545050A7E380 500GB           | 4         | 6      | 0.8%    |
| Hitachi HTS543216L9A300 160GB           | 4         | 4      | 0.8%    |
| Hitachi HTS542516K9SA00 160GB           | 4         | 4      | 0.8%    |
| Hitachi HTS541680J9SA00 80GB            | 4         | 4      | 0.8%    |
| HGST HTS725050A7E630 500GB              | 4         | 4      | 0.8%    |
| Toshiba MQ01ABF032 320GB                | 3         | 3      | 0.6%    |
| Seagate ST980811AS 80GB                 | 3         | 3      | 0.6%    |
| Seagate ST9250410AS 250GB               | 3         | 3      | 0.6%    |
| Seagate ST500LM021-1KJ152 500GB         | 3         | 3      | 0.6%    |
| Seagate ST500LM012 HN-M500MBB 500GB     | 3         | 4      | 0.6%    |
| Samsung Electronics HM321HI 320GB       | 3         | 5      | 0.6%    |
| Hitachi HTS545025B9A300 250GB           | 3         | 8      | 0.6%    |
| Hitachi HTS543232A7A384 320GB           | 3         | 5      | 0.6%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 122       | 173    | 24.55%  |
| Hitachi             | 79        | 118    | 15.9%   |
| Toshiba             | 74        | 114    | 14.89%  |
| HGST                | 69        | 112    | 13.88%  |
| WDC                 | 57        | 78     | 11.47%  |
| Samsung Electronics | 21        | 34     | 4.23%   |
| Kingston            | 19        | 29     | 3.82%   |
| Fujitsu             | 16        | 24     | 3.22%   |
| Intel               | 12        | 22     | 2.41%   |
| SK hynix            | 6         | 7      | 1.21%   |
| SanDisk             | 3         | 4      | 0.6%    |
| A-DATA Technology   | 3         | 3      | 0.6%    |
| Intenso             | 2         | 2      | 0.4%    |
| IBM/Hitachi         | 2         | 2      | 0.4%    |
| SPCC                | 1         | 1      | 0.2%    |
| R580                | 1         | 1      | 0.2%    |
| OCZ-AGIL            | 1         | 1      | 0.2%    |
| LITEON              | 1         | 1      | 0.2%    |
| Kingmax             | 1         | 1      | 0.2%    |
| JMicron Technology  | 1         | 1      | 0.2%    |
| Initio              | 1         | 2      | 0.2%    |
| CSD                 | 1         | 2      | 0.2%    |
| Crucial             | 1         | 1      | 0.2%    |
| China               | 1         | 1      | 0.2%    |
| Apple               | 1         | 5      | 0.2%    |
| Apacer              | 1         | 2      | 0.2%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 122       | 173    | 28.5%   |
| Hitachi             | 79        | 118    | 18.46%  |
| HGST                | 69        | 112    | 16.12%  |
| Toshiba             | 68        | 100    | 15.89%  |
| WDC                 | 55        | 76     | 12.85%  |
| Fujitsu             | 16        | 24     | 3.74%   |
| Samsung Electronics | 15        | 20     | 3.5%    |
| IBM/Hitachi         | 2         | 2      | 0.47%   |
| Initio              | 1         | 2      | 0.23%   |
| CSD                 | 1         | 2      | 0.23%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 418       | 629    | 85.83%  |
| SSD     | 65        | 107    | 13.35%  |
| NVMe    | 3         | 4      | 0.62%   |
| Unknown | 1         | 1      | 0.21%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-22A0RT0 500GB       | 1         | 7      | 7.14%   |
| WDC WD3200BVVT-63A26Y0 320GB       | 1         | 1      | 7.14%   |
| WDC WD3200BPVT-24JJ5T0 320GB       | 1         | 1      | 7.14%   |
| WDC WD3200BEVT-08A23T1 320GB       | 1         | 1      | 7.14%   |
| WDC WD2500LPCX-24C6HT0 250GB       | 1         | 1      | 7.14%   |
| WDC WD1600BEVT-22ZCT0 160GB        | 1         | 1      | 7.14%   |
| Toshiba MQ01ABD050V 500GB          | 1         | 1      | 7.14%   |
| Toshiba MK6475GSX 640GB            | 1         | 1      | 7.14%   |
| Toshiba MK3275GSX 320GB            | 1         | 1      | 7.14%   |
| Seagate ST9160821AS 160GB          | 1         | 1      | 7.14%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 7.14%   |
| Samsung Electronics HM060HI 64GB   | 1         | 1      | 7.14%   |
| Intel SSDPEKKW256G7 256GB          | 1         | 1      | 7.14%   |
| Hitachi HTS723232A7A364 320GB      | 1         | 1      | 7.14%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 12     | 42.86%  |
| Toshiba             | 3         | 3      | 21.43%  |
| Seagate             | 2         | 2      | 14.29%  |
| Samsung Electronics | 1         | 1      | 7.14%   |
| Intel               | 1         | 1      | 7.14%   |
| Hitachi             | 1         | 1      | 7.14%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1229      | 2155   | 51.27%  |
| Detected | 675       | 1107   | 28.16%  |
| Malfunc  | 479       | 741    | 19.98%  |
| Failed   | 14        | 20     | 0.58%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1742      | 72.95%  |
| AMD                              | 249       | 10.43%  |
| Samsung Electronics              | 119       | 4.98%   |
| SanDisk                          | 57        | 2.39%   |
| SK hynix                         | 43        | 1.8%    |
| Kingston Technology Company      | 39        | 1.63%   |
| Toshiba America Info Systems     | 28        | 1.17%   |
| Micron Technology                | 16        | 0.67%   |
| KIOXIA                           | 15        | 0.63%   |
| Silicon Integrated Systems [SiS] | 13        | 0.54%   |
| Nvidia                           | 12        | 0.5%    |
| Phison Electronics               | 11        | 0.46%   |
| VIA Technologies                 | 7         | 0.29%   |
| Silicon Motion                   | 6         | 0.25%   |
| Solid State Storage Technology   | 5         | 0.21%   |
| JMicron Technology               | 5         | 0.21%   |
| Micron/Crucial Technology        | 4         | 0.17%   |
| Apple                            | 3         | 0.13%   |
| ADATA Technology                 | 3         | 0.13%   |
| Union Memory (Shenzhen)          | 2         | 0.08%   |
| Silicon Image                    | 2         | 0.08%   |
| Lite-On Technology               | 2         | 0.08%   |
| Shenzhen Longsys Electronics     | 1         | 0.04%   |
| Seagate Technology               | 1         | 0.04%   |
| Realtek Semiconductor            | 1         | 0.04%   |
| O2 Micro                         | 1         | 0.04%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 198       | 7.35%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 181       | 6.72%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 178       | 6.6%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 151       | 5.6%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 131       | 4.86%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 117       | 4.34%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 94        | 3.49%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 88        | 3.27%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 78        | 2.89%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 75        | 2.78%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 66        | 2.45%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 63        | 2.34%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 55        | 2.04%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 49        | 1.82%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 49        | 1.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 46        | 1.71%   |
| Samsung NVMe SSD Controller 980                                                  | 41        | 1.52%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 41        | 1.52%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 38        | 1.41%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 36        | 1.34%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 35        | 1.3%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 35        | 1.3%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 32        | 1.19%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 31        | 1.15%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 31        | 1.15%   |
| Intel Volume Management Device NVMe RAID Controller                              | 29        | 1.08%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 27        | 1%      |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 23        | 0.85%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 21        | 0.78%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 21        | 0.78%   |
| Intel Comet Lake SATA AHCI Controller                                            | 19        | 0.71%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 18        | 0.67%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 18        | 0.67%   |
| Intel Tiger Lake-LP SATA Controller                                              | 17        | 0.63%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 17        | 0.63%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 15        | 0.56%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 15        | 0.56%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 14        | 0.52%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 14        | 0.52%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 13        | 0.48%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1728      | 67.47%  |
| NVMe | 354       | 13.82%  |
| IDE  | 329       | 12.85%  |
| RAID | 150       | 5.86%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 1864      | 85.86%  |
| AMD          | 305       | 14.05%  |
| CentaurHauls | 2         | 0.09%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz           | 49        | 2.25%   |
| Intel Celeron CPU 1000M @ 1.80GHz           | 42        | 1.93%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 35        | 1.61%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 33        | 1.52%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 27        | 1.24%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 27        | 1.24%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 26        | 1.19%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 24        | 1.1%    |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 22        | 1.01%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 21        | 0.96%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 21        | 0.96%   |
| Intel Core i3-7020U CPU @ 2.30GHz           | 21        | 0.96%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 19        | 0.87%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 18        | 0.83%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz        | 18        | 0.83%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 18        | 0.83%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 17        | 0.78%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz        | 17        | 0.78%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 16        | 0.73%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 16        | 0.73%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 15        | 0.69%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 15        | 0.69%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 15        | 0.69%   |
| Intel Core i3 CPU M 350 @ 2.27GHz           | 15        | 0.69%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 15        | 0.69%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 14        | 0.64%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 14        | 0.64%   |
| Intel Core i5 CPU M 560 @ 2.67GHz           | 14        | 0.64%   |
| Intel Core i5 CPU M 540 @ 2.53GHz           | 14        | 0.64%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 14        | 0.64%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 14        | 0.64%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 14        | 0.64%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 13        | 0.6%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 13        | 0.6%    |
| Intel Core i7-6600U CPU @ 2.60GHz           | 13        | 0.6%    |
| Intel Core i5-3210M CPU @ 2.50GHz           | 13        | 0.6%    |
| Intel Core i3-4005U CPU @ 1.70GHz           | 13        | 0.6%    |
| Intel Celeron N4000 CPU @ 1.10GHz           | 13        | 0.6%    |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 13        | 0.6%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 12        | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 520       | 23.9%   |
| Intel Core i7           | 277       | 12.73%  |
| Intel Core i3           | 274       | 12.59%  |
| Intel Celeron           | 198       | 9.1%    |
| Intel Core 2 Duo        | 188       | 8.64%   |
| Intel Pentium           | 91        | 4.18%   |
| Intel Atom              | 74        | 3.4%    |
| Other                   | 67        | 3.08%   |
| Intel Pentium Dual-Core | 45        | 2.07%   |
| AMD Ryzen 5             | 41        | 1.88%   |
| Intel Pentium Dual      | 31        | 1.42%   |
| AMD Ryzen 7             | 31        | 1.42%   |
| AMD A4                  | 29        | 1.33%   |
| AMD A8                  | 26        | 1.19%   |
| Intel Core 2            | 24        | 1.1%    |
| Intel Genuine           | 19        | 0.87%   |
| AMD E1                  | 18        | 0.83%   |
| AMD A6                  | 18        | 0.83%   |
| AMD E                   | 17        | 0.78%   |
| Intel Pentium Silver    | 16        | 0.74%   |
| AMD E2                  | 14        | 0.64%   |
| Intel Celeron M         | 13        | 0.6%    |
| Intel Celeron Dual-Core | 13        | 0.6%    |
| AMD Ryzen 3             | 12        | 0.55%   |
| AMD A10                 | 11        | 0.51%   |
| Intel Pentium M         | 9         | 0.41%   |
| Intel Core Duo          | 8         | 0.37%   |
| AMD Athlon II           | 7         | 0.32%   |
| AMD Turion 64 X2 Mobile | 6         | 0.28%   |
| AMD Ryzen 7 PRO         | 6         | 0.28%   |
| AMD FX                  | 6         | 0.28%   |
| AMD C-60                | 5         | 0.23%   |
| AMD Ryzen 9             | 4         | 0.18%   |
| AMD Ryzen 5 PRO         | 4         | 0.18%   |
| AMD Mobile Sempron      | 4         | 0.18%   |
| AMD C-50                | 4         | 0.18%   |
| AMD Athlon X2           | 4         | 0.18%   |
| Intel Core i9           | 3         | 0.14%   |
| AMD Athlon II Dual-Core | 3         | 0.14%   |
| AMD Athlon 64 X2        | 3         | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1463      | 67.17%  |
| 4      | 446       | 20.48%  |
| 1      | 134       | 6.15%   |
| 6      | 78        | 3.58%   |
| 8      | 42        | 1.93%   |
| 10     | 7         | 0.32%   |
| 14     | 5         | 0.23%   |
| 12     | 3         | 0.14%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2171      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1281      | 58.63%  |
| 1      | 904       | 41.37%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2096      | 96.06%  |
| 32-bit         | 54        | 2.47%   |
| Unknown        | 32        | 1.47%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 303       | 13.42%  |
| 0x206a7    | 184       | 8.15%   |
| 0x306a9    | 172       | 7.62%   |
| 0x1067a    | 148       | 6.55%   |
| 0x20655    | 109       | 4.83%   |
| 0x40651    | 86        | 3.81%   |
| 0x306d4    | 79        | 3.5%    |
| 0x406e3    | 76        | 3.37%   |
| 0x6fd      | 74        | 3.28%   |
| 0x806e9    | 57        | 2.52%   |
| 0x806ea    | 53        | 2.35%   |
| 0x306c3    | 51        | 2.26%   |
| 0x406c4    | 43        | 1.9%    |
| 0x906ea    | 40        | 1.77%   |
| 0x806ec    | 38        | 1.68%   |
| 0x10676    | 38        | 1.68%   |
| 0x20652    | 35        | 1.55%   |
| 0x106ca    | 33        | 1.46%   |
| 0x806c1    | 31        | 1.37%   |
| 0x30678    | 30        | 1.33%   |
| 0x506c9    | 29        | 1.28%   |
| 0x05000119 | 27        | 1.2%    |
| 0x706a1    | 25        | 1.11%   |
| 0x07030105 | 24        | 1.06%   |
| 0x906e9    | 21        | 0.93%   |
| 0x406c3    | 20        | 0.89%   |
| 0x806eb    | 19        | 0.84%   |
| 0x706e5    | 19        | 0.84%   |
| 0x6fb      | 19        | 0.84%   |
| 0x106c2    | 19        | 0.84%   |
| 0x506e3    | 18        | 0.8%    |
| 0x6f6      | 16        | 0.71%   |
| 0x0a50000c | 16        | 0.71%   |
| 0x08600106 | 16        | 0.71%   |
| 0x0700010f | 16        | 0.71%   |
| 0x06001119 | 13        | 0.58%   |
| 0x6ec      | 12        | 0.53%   |
| 0x05000029 | 11        | 0.49%   |
| 0x010000c8 | 11        | 0.49%   |
| 0x6f2      | 10        | 0.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 282       | 12.98%  |
| Penryn           | 191       | 8.79%   |
| SandyBridge      | 190       | 8.75%   |
| IvyBridge        | 182       | 8.38%   |
| Haswell          | 158       | 7.27%   |
| Westmere         | 150       | 6.91%   |
| Core             | 145       | 6.68%   |
| Skylake          | 113       | 5.2%    |
| Silvermont       | 104       | 4.79%   |
| Broadwell        | 92        | 4.24%   |
| Bonnell          | 54        | 2.49%   |
| Bobcat           | 43        | 1.98%   |
| Puma             | 36        | 1.66%   |
| Goldmont         | 36        | 1.66%   |
| TigerLake        | 35        | 1.61%   |
| P6               | 33        | 1.52%   |
| Goldmont plus    | 33        | 1.52%   |
| Icelake          | 32        | 1.47%   |
| Zen 2            | 29        | 1.34%   |
| Zen 3            | 27        | 1.24%   |
| Unknown          | 26        | 1.2%    |
| Excavator        | 25        | 1.15%   |
| Jaguar           | 19        | 0.87%   |
| Piledriver       | 18        | 0.83%   |
| K10              | 17        | 0.78%   |
| K8 Hammer        | 16        | 0.74%   |
| Zen+             | 15        | 0.69%   |
| Zen              | 15        | 0.69%   |
| Steamroller      | 13        | 0.6%    |
| Alderlake Hybrid | 12        | 0.55%   |
| CometLake        | 10        | 0.46%   |
| K10 Llano        | 7         | 0.32%   |
| K8 & K10 hybrid  | 6         | 0.28%   |
| Nehalem          | 5         | 0.23%   |
| Tremont          | 2         | 0.09%   |
| NetBurst         | 1         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1671      | 62.7%   |
| Nvidia                           | 504       | 18.91%  |
| AMD                              | 476       | 17.86%  |
| VIA Technologies                 | 7         | 0.26%   |
| Silicon Integrated Systems [SiS] | 7         | 0.26%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 180       | 6.33%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 173       | 6.08%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 153       | 5.38%   |
| Intel Core Processor Integrated Graphics Controller                                      | 105       | 3.69%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 95        | 3.34%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 82        | 2.88%   |
| Intel HD Graphics 5500                                                                   | 81        | 2.85%   |
| Intel HD Graphics 620                                                                    | 76        | 2.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 66        | 2.32%   |
| Intel UHD Graphics 620                                                                   | 59        | 2.07%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 57        | 2%      |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 57        | 2%      |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 57        | 2%      |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 52        | 1.83%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 46        | 1.62%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 38        | 1.34%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 38        | 1.34%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 38        | 1.34%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 34        | 1.2%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 33        | 1.16%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 31        | 1.09%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 31        | 1.09%   |
| AMD Renoir                                                                               | 29        | 1.02%   |
| Intel HD Graphics 500                                                                    | 28        | 0.98%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 27        | 0.95%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 27        | 0.95%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 26        | 0.91%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 23        | 0.81%   |
| Intel HD Graphics 530                                                                    | 22        | 0.77%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 21        | 0.74%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520/610 Mobile]                         | 21        | 0.74%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 21        | 0.74%   |
| Nvidia GP108M [GeForce MX150]                                                            | 19        | 0.67%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 19        | 0.67%   |
| Intel HD Graphics 630                                                                    | 19        | 0.67%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 19        | 0.67%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 17        | 0.6%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 17        | 0.6%    |
| Nvidia GM108M [GeForce MX110]                                                            | 16        | 0.56%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 16        | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 1200      | 55.2%   |
| Intel + Nvidia | 364       | 16.74%  |
| 1 x AMD        | 286       | 13.16%  |
| 1 x Nvidia     | 112       | 5.15%   |
| Intel + AMD    | 102       | 4.69%   |
| 2 x AMD        | 62        | 2.85%   |
| AMD + Nvidia   | 27        | 1.24%   |
| 1 x VIA        | 7         | 0.32%   |
| 1 x SiS        | 7         | 0.32%   |
| 2 x Intel      | 5         | 0.23%   |
| Other          | 1         | 0.05%   |
| 2 x Nvidia     | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2032      | 92.7%   |
| Proprietary | 125       | 5.7%    |
| Unknown     | 35        | 1.6%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1299      | 57.94%  |
| 0.01-0.5   | 391       | 17.44%  |
| 1.01-2.0   | 295       | 13.16%  |
| 0.51-1.0   | 133       | 5.93%   |
| 3.01-4.0   | 98        | 4.37%   |
| 5.01-6.0   | 16        | 0.71%   |
| 7.01-8.0   | 5         | 0.22%   |
| 2.01-3.0   | 4         | 0.18%   |
| 8.01-16.0  | 1         | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 464       | 19.85%  |
| AU Optronics            | 432       | 18.49%  |
| Samsung Electronics     | 338       | 14.46%  |
| Chimei Innolux          | 283       | 12.11%  |
| BOE                     | 239       | 10.23%  |
| Chi Mei Optoelectronics | 101       | 4.32%   |
| Lenovo                  | 82        | 3.51%   |
| Goldstar                | 50        | 2.14%   |
| LG Philips              | 38        | 1.63%   |
| Dell                    | 30        | 1.28%   |
| InfoVision              | 26        | 1.11%   |
| PANDA                   | 18        | 0.77%   |
| Philips                 | 15        | 0.64%   |
| CPT                     | 14        | 0.6%    |
| BenQ                    | 14        | 0.6%    |
| Apple                   | 14        | 0.6%    |
| Hewlett-Packard         | 13        | 0.56%   |
| Acer                    | 13        | 0.56%   |
| AOC                     | 12        | 0.51%   |
| HannStar                | 11        | 0.47%   |
| Sharp                   | 10        | 0.43%   |
| Sony                    | 9         | 0.39%   |
| ASUSTek Computer        | 9         | 0.39%   |
| Quanta Display          | 8         | 0.34%   |
| InnoLux Display         | 8         | 0.34%   |
| Toshiba                 | 7         | 0.3%    |
| Ancor Communications    | 7         | 0.3%    |
| Vestel Elektronik       | 6         | 0.26%   |
| Fujitsu Siemens         | 6         | 0.26%   |
| Panasonic               | 4         | 0.17%   |
| IBM                     | 4         | 0.17%   |
| Valve                   | 3         | 0.13%   |
| NEC Computers           | 3         | 0.13%   |
| Eizo                    | 3         | 0.13%   |
| CSO                     | 3         | 0.13%   |
| ViewSonic               | 2         | 0.09%   |
| TMX                     | 2         | 0.09%   |
| SKY                     | 2         | 0.09%   |
| Plain Tree Systems      | 2         | 0.09%   |
| OEM                     | 2         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 50        | 2.12%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 39        | 1.65%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 36        | 1.53%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 25        | 1.06%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 24        | 1.02%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 22        | 0.93%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 22        | 0.93%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 19        | 0.81%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch                  | 15        | 0.64%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 15        | 0.64%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 15        | 0.64%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch            | 14        | 0.59%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 14        | 0.59%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 14        | 0.59%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 13        | 0.55%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 12        | 0.51%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 12        | 0.51%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 12        | 0.51%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 12        | 0.51%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch     | 11        | 0.47%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 11        | 0.47%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 11        | 0.47%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 11        | 0.47%   |
| LG Display LCD Monitor LGD02AD 1366x768 344x194mm 15.5-inch              | 10        | 0.42%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 10        | 0.42%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 10        | 0.42%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch              | 9         | 0.38%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 9         | 0.38%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 9         | 0.38%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 8         | 0.34%   |
| LG Philips LP154WX4-TLC8 LPL0120 1280x800 331x207mm 15.4-inch            | 8         | 0.34%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x190mm 14.1-inch                  | 8         | 0.34%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 8         | 0.34%   |
| Chi Mei Optoelectronics LCD Monitor CMO1526 1280x800 331x207mm 15.4-inch | 8         | 0.34%   |
| BOE LCD Monitor BOE061D 1366x768 309x173mm 13.9-inch                     | 8         | 0.34%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 8         | 0.34%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch            | 8         | 0.34%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 8         | 0.34%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 303x190mm 14.1-inch     | 7         | 0.3%    |
| Samsung Electronics LCD Monitor SEC3245 1280x800 331x207mm 15.4-inch     | 7         | 0.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 899       | 39.85%  |
| 1920x1080 (FHD)    | 700       | 31.03%  |
| 1280x800 (WXGA)    | 177       | 7.85%   |
| 1600x900 (HD+)     | 146       | 6.47%   |
| 1440x900 (WXGA+)   | 61        | 2.7%    |
| 3840x2160 (4K)     | 47        | 2.08%   |
| 1024x600           | 39        | 1.73%   |
| 1920x1200 (WUXGA)  | 27        | 1.2%    |
| 1680x1050 (WSXGA+) | 24        | 1.06%   |
| 2560x1440 (QHD)    | 22        | 0.98%   |
| 1280x1024 (SXGA)   | 18        | 0.8%    |
| 1024x768 (XGA)     | 16        | 0.71%   |
| 2880x1800          | 11        | 0.49%   |
| 2560x1600          | 11        | 0.49%   |
| 1360x768           | 8         | 0.35%   |
| 2560x1080          | 6         | 0.27%   |
| 1920x540           | 6         | 0.27%   |
| 800x1280           | 4         | 0.18%   |
| 1400x1050          | 4         | 0.18%   |
| 3840x2400          | 3         | 0.13%   |
| 3440x1440          | 3         | 0.13%   |
| 2880x1620          | 3         | 0.13%   |
| 1680x945           | 3         | 0.13%   |
| 3200x2000          | 2         | 0.09%   |
| 2288x1287          | 2         | 0.09%   |
| 2160x1440          | 2         | 0.09%   |
| 1600x1200          | 2         | 0.09%   |
| 1280x768           | 2         | 0.09%   |
| 5760x2160          | 1         | 0.04%   |
| 4093x4093          | 1         | 0.04%   |
| 2304x1440          | 1         | 0.04%   |
| 1920x1280          | 1         | 0.04%   |
| 1800x1440          | 1         | 0.04%   |
| 1600x2560          | 1         | 0.04%   |
| 1280x720 (HD)      | 1         | 0.04%   |
| Unknown            | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1240      | 52.86%  |
| 14      | 276       | 11.76%  |
| 13      | 182       | 7.76%   |
| 17      | 145       | 6.18%   |
| 12      | 86        | 3.67%   |
| 24      | 51        | 2.17%   |
| 10      | 47        | 2%      |
| 23      | 46        | 1.96%   |
| 21      | 42        | 1.79%   |
| 11      | 40        | 1.71%   |
| 27      | 38        | 1.62%   |
| 18      | 25        | 1.07%   |
| 19      | 14        | 0.6%    |
| 16      | 13        | 0.55%   |
| Unknown | 12        | 0.51%   |
| 22      | 11        | 0.47%   |
| 84      | 8         | 0.34%   |
| 34      | 8         | 0.34%   |
| 31      | 8         | 0.34%   |
| 20      | 8         | 0.34%   |
| 72      | 5         | 0.21%   |
| 54      | 5         | 0.21%   |
| 32      | 5         | 0.21%   |
| 40      | 4         | 0.17%   |
| 8       | 4         | 0.17%   |
| 65      | 3         | 0.13%   |
| 7       | 3         | 0.13%   |
| 33      | 2         | 0.09%   |
| 25      | 2         | 0.09%   |
| 142     | 1         | 0.04%   |
| 60      | 1         | 0.04%   |
| 58      | 1         | 0.04%   |
| 52      | 1         | 0.04%   |
| 49      | 1         | 0.04%   |
| 48      | 1         | 0.04%   |
| 43      | 1         | 0.04%   |
| 42      | 1         | 0.04%   |
| 41      | 1         | 0.04%   |
| 39      | 1         | 0.04%   |
| 29      | 1         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 1590      | 68.18%  |
| 201-300        | 248       | 10.63%  |
| 351-400        | 197       | 8.45%   |
| 501-600        | 131       | 5.62%   |
| 401-500        | 83        | 3.56%   |
| 701-800        | 15        | 0.64%   |
| 1501-2000      | 13        | 0.56%   |
| 1001-1500      | 13        | 0.56%   |
| 601-700        | 12        | 0.51%   |
| Unknown        | 12        | 0.51%   |
| 801-900        | 5         | 0.21%   |
| 101-200        | 5         | 0.21%   |
| 1-100          | 4         | 0.17%   |
| 901-1000       | 3         | 0.13%   |
| More than 2000 | 1         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1763      | 81.92%  |
| 16/10   | 316       | 14.68%  |
| 4/3     | 25        | 1.16%   |
| 5/4     | 17        | 0.79%   |
| 3/2     | 9         | 0.42%   |
| 21/9    | 8         | 0.37%   |
| Unknown | 8         | 0.37%   |
| 0.67    | 3         | 0.14%   |
| 6/5     | 1         | 0.05%   |
| 1.00    | 1         | 0.05%   |
| 0.63    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1237      | 52.86%  |
| 81-90          | 391       | 16.71%  |
| 201-250        | 116       | 4.96%   |
| 121-130        | 106       | 4.53%   |
| 61-70          | 84        | 3.59%   |
| 71-80          | 65        | 2.78%   |
| 41-50          | 47        | 2.01%   |
| 51-60          | 40        | 1.71%   |
| 301-350        | 38        | 1.62%   |
| 151-200        | 34        | 1.45%   |
| 131-140        | 33        | 1.41%   |
| 141-150        | 30        | 1.28%   |
| More than 1000 | 26        | 1.11%   |
| 351-500        | 23        | 0.98%   |
| 251-300        | 23        | 0.98%   |
| Unknown        | 12        | 0.51%   |
| 1-40           | 9         | 0.38%   |
| 111-120        | 9         | 0.38%   |
| 91-100         | 9         | 0.38%   |
| 501-1000       | 8         | 0.34%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 930       | 40.35%  |
| 121-160       | 783       | 33.97%  |
| 51-100        | 454       | 19.7%   |
| 161-240       | 81        | 3.51%   |
| More than 240 | 26        | 1.13%   |
| 1-50          | 19        | 0.82%   |
| Unknown       | 12        | 0.52%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1933      | 86.29%  |
| 2     | 255       | 11.38%  |
| 0     | 30        | 1.34%   |
| 3     | 18        | 0.8%    |
| 4     | 4         | 0.18%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1088      | 30.57%  |
| Intel                             | 1027      | 28.86%  |
| Qualcomm Atheros                  | 641       | 18.01%  |
| Broadcom                          | 270       | 7.59%   |
| Ralink                            | 100       | 2.81%   |
| Broadcom Limited                  | 97        | 2.73%   |
| Marvell Technology Group          | 48        | 1.35%   |
| MediaTek                          | 43        | 1.21%   |
| Dell                              | 27        | 0.76%   |
| Hewlett-Packard                   | 21        | 0.59%   |
| Ericsson Business Mobile Networks | 20        | 0.56%   |
| TP-Link                           | 16        | 0.45%   |
| Sierra Wireless                   | 14        | 0.39%   |
| Huawei Technologies               | 14        | 0.39%   |
| Samsung Electronics               | 13        | 0.37%   |
| JMicron Technology                | 12        | 0.34%   |
| Silicon Integrated Systems [SiS]  | 11        | 0.31%   |
| Ralink Technology                 | 11        | 0.31%   |
| Attansic Technology               | 11        | 0.31%   |
| Xiaomi                            | 10        | 0.28%   |
| Qualcomm Atheros Communications   | 7         | 0.2%    |
| ASIX Electronics                  | 7         | 0.2%    |
| Nvidia                            | 6         | 0.17%   |
| VIA Technologies                  | 5         | 0.14%   |
| Lenovo                            | 5         | 0.14%   |
| DisplayLink                       | 5         | 0.14%   |
| D-Link                            | 3         | 0.08%   |
| ASUSTek Computer                  | 3         | 0.08%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.06%   |
| NetGear                           | 2         | 0.06%   |
| Belkin Components                 | 2         | 0.06%   |
| Apple                             | 2         | 0.06%   |
| WEMOS.CC                          | 1         | 0.03%   |
| Spreadtrum Communications         | 1         | 0.03%   |
| Qualcomm                          | 1         | 0.03%   |
| QinHeng Electronics               | 1         | 0.03%   |
| OPPO Electronics                  | 1         | 0.03%   |
| Motorola PCS                      | 1         | 0.03%   |
| Microsoft                         | 1         | 0.03%   |
| Micro Star International          | 1         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 645       | 14.95%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 316       | 7.32%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 121       | 2.8%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 116       | 2.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 115       | 2.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 110       | 2.55%   |
| Intel Wireless 8265 / 8275                                              | 82        | 1.9%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 78        | 1.81%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 78        | 1.81%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 72        | 1.67%   |
| Intel Wireless 7260                                                     | 68        | 1.58%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 67        | 1.55%   |
| Intel 82577LM Gigabit Network Connection                                | 65        | 1.51%   |
| Intel Wireless 7265                                                     | 62        | 1.44%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 61        | 1.41%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 58        | 1.34%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 54        | 1.25%   |
| Intel 82567LM Gigabit Network Connection                                | 54        | 1.25%   |
| Intel Centrino Advanced-N 6200                                          | 53        | 1.23%   |
| Intel Wireless 3165                                                     | 42        | 0.97%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 39        | 0.9%    |
| Intel Centrino Ultimate-N 6300                                          | 38        | 0.88%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 36        | 0.83%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 36        | 0.83%   |
| Intel Wireless 8260                                                     | 35        | 0.81%   |
| Intel Wireless 3160                                                     | 35        | 0.81%   |
| Intel Wi-Fi 6 AX200                                                     | 33        | 0.76%   |
| Intel Ethernet Connection (4) I219-LM                                   | 32        | 0.74%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 31        | 0.72%   |
| Intel WiFi Link 5100                                                    | 31        | 0.72%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 29        | 0.67%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 29        | 0.67%   |
| Intel Wi-Fi 6 AX201                                                     | 29        | 0.67%   |
| Broadcom BCM43142 802.11b/g/n                                           | 29        | 0.67%   |
| Intel Ethernet Connection I218-LM                                       | 28        | 0.65%   |
| Intel Ethernet Connection (3) I218-LM                                   | 28        | 0.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 27        | 0.63%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 25        | 0.58%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 23        | 0.53%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 22        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 965       | 43.22%  |
| Qualcomm Atheros                | 568       | 25.44%  |
| Realtek Semiconductor           | 256       | 11.46%  |
| Broadcom                        | 180       | 8.06%   |
| Ralink                          | 100       | 4.48%   |
| Broadcom Limited                | 46        | 2.06%   |
| MediaTek                        | 41        | 1.84%   |
| Dell                            | 16        | 0.72%   |
| Sierra Wireless                 | 14        | 0.63%   |
| TP-Link                         | 11        | 0.49%   |
| Ralink Technology               | 11        | 0.49%   |
| Qualcomm Atheros Communications | 7         | 0.31%   |
| Hewlett-Packard                 | 3         | 0.13%   |
| D-Link                          | 3         | 0.13%   |
| ASUSTek Computer                | 3         | 0.13%   |
| NetGear                         | 2         | 0.09%   |
| Belkin Components               | 2         | 0.09%   |
| Qualcomm                        | 1         | 0.04%   |
| Microsoft                       | 1         | 0.04%   |
| Micro Star International        | 1         | 0.04%   |
| Fujitsu Siemens Computers       | 1         | 0.04%   |
| Edimax Technology               | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 121       | 5.4%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 116       | 5.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 110       | 4.91%   |
| Intel Wireless 8265 / 8275                                              | 82        | 3.66%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 78        | 3.48%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 78        | 3.48%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 72        | 3.21%   |
| Intel Wireless 7260                                                     | 68        | 3.03%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 67        | 2.99%   |
| Intel Wireless 7265                                                     | 62        | 2.77%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 61        | 2.72%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 58        | 2.59%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 54        | 2.41%   |
| Intel Centrino Advanced-N 6200                                          | 53        | 2.36%   |
| Intel Wireless 3165                                                     | 42        | 1.87%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 39        | 1.74%   |
| Intel Centrino Ultimate-N 6300                                          | 38        | 1.69%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 36        | 1.61%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 36        | 1.61%   |
| Intel Wireless 8260                                                     | 35        | 1.56%   |
| Intel Wireless 3160                                                     | 35        | 1.56%   |
| Intel Wi-Fi 6 AX200                                                     | 33        | 1.47%   |
| Intel WiFi Link 5100                                                    | 31        | 1.38%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 29        | 1.29%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 29        | 1.29%   |
| Intel Wi-Fi 6 AX201                                                     | 29        | 1.29%   |
| Broadcom BCM43142 802.11b/g/n                                           | 29        | 1.29%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 27        | 1.2%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 25        | 1.12%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 23        | 1.03%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 22        | 0.98%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 21        | 0.94%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 21        | 0.94%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 20        | 0.89%   |
| Intel Ultimate N WiFi Link 5300                                         | 19        | 0.85%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 18        | 0.8%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 17        | 0.76%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 17        | 0.76%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 17        | 0.76%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 16        | 0.71%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1013      | 50.52%  |
| Intel                            | 503       | 25.09%  |
| Qualcomm Atheros                 | 158       | 7.88%   |
| Broadcom                         | 113       | 5.64%   |
| Broadcom Limited                 | 52        | 2.59%   |
| Marvell Technology Group         | 48        | 2.39%   |
| Samsung Electronics              | 13        | 0.65%   |
| Huawei Technologies              | 13        | 0.65%   |
| JMicron Technology               | 12        | 0.6%    |
| Silicon Integrated Systems [SiS] | 11        | 0.55%   |
| Attansic Technology              | 11        | 0.55%   |
| Xiaomi                           | 10        | 0.5%    |
| ASIX Electronics                 | 7         | 0.35%   |
| Nvidia                           | 6         | 0.3%    |
| VIA Technologies                 | 5         | 0.25%   |
| TP-Link                          | 5         | 0.25%   |
| Lenovo                           | 5         | 0.25%   |
| DisplayLink                      | 5         | 0.25%   |
| ZTE WCDMA Technologies MSM       | 2         | 0.1%    |
| MediaTek                         | 2         | 0.1%    |
| Hewlett-Packard                  | 2         | 0.1%    |
| Apple                            | 2         | 0.1%    |
| Spreadtrum Communications        | 1         | 0.05%   |
| OPPO Electronics                 | 1         | 0.05%   |
| Motorola PCS                     | 1         | 0.05%   |
| LG Electronics                   | 1         | 0.05%   |
| ICS Advent                       | 1         | 0.05%   |
| Davicom Semiconductor            | 1         | 0.05%   |
| 3DSP                             | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 645       | 32.04%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 316       | 15.7%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 115       | 5.71%   |
| Intel 82577LM Gigabit Network Connection                          | 65        | 3.23%   |
| Intel 82567LM Gigabit Network Connection                          | 54        | 2.68%   |
| Intel Ethernet Connection (4) I219-LM                             | 32        | 1.59%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 31        | 1.54%   |
| Intel Ethernet Connection I218-LM                                 | 28        | 1.39%   |
| Intel Ethernet Connection (3) I218-LM                             | 28        | 1.39%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 22        | 1.09%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 22        | 1.09%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 21        | 1.04%   |
| Intel 82566MM Gigabit Network Connection                          | 21        | 1.04%   |
| Intel Ethernet Connection I217-LM                                 | 19        | 0.94%   |
| Intel Ethernet Connection I219-LM                                 | 18        | 0.89%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 16        | 0.79%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 16        | 0.79%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 16        | 0.79%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 15        | 0.75%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 14        | 0.7%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 14        | 0.7%    |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 14        | 0.7%    |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 14        | 0.7%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 12        | 0.6%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 12        | 0.6%    |
| Intel 82579V Gigabit Network Connection                           | 12        | 0.6%    |
| Huawei JKM-LX1                                                    | 12        | 0.6%    |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 12        | 0.6%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 11        | 0.55%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 11        | 0.55%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 11        | 0.55%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 11        | 0.55%   |
| Attansic AR8152 v2.0 Fast Ethernet                                | 11        | 0.55%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 10        | 0.5%    |
| Broadcom BCM4401-B0 100Base-TX                                    | 10        | 0.5%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 9         | 0.45%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 9         | 0.45%   |
| Intel Ethernet Connection (2) I219-LM                             | 9         | 0.45%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 9         | 0.45%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 8         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2139      | 51.64%  |
| Ethernet | 1944      | 46.93%  |
| Modem    | 58        | 1.4%    |
| Unknown  | 1         | 0.02%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1776      | 74.94%  |
| Ethernet | 594       | 25.06%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1874      | 86.16%  |
| 1     | 261       | 12%     |
| 0     | 33        | 1.52%   |
| 3     | 7         | 0.32%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1864      | 81.97%  |
| Yes  | 410       | 18.03%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 571       | 34.73%  |
| Qualcomm Atheros Communications | 182       | 11.07%  |
| Broadcom                        | 149       | 9.06%   |
| Realtek Semiconductor           | 138       | 8.39%   |
| Lite-On Technology              | 97        | 5.9%    |
| IMC Networks                    | 89        | 5.41%   |
| Dell                            | 83        | 5.05%   |
| Hewlett-Packard                 | 73        | 4.44%   |
| Foxconn / Hon Hai               | 69        | 4.2%    |
| Ralink                          | 67        | 4.08%   |
| Cambridge Silicon Radio         | 28        | 1.7%    |
| Toshiba                         | 25        | 1.52%   |
| ASUSTek Computer                | 12        | 0.73%   |
| Ralink Technology               | 10        | 0.61%   |
| Apple                           | 10        | 0.61%   |
| Realtek                         | 8         | 0.49%   |
| Askey Computer                  | 8         | 0.49%   |
| Chicony Electronics             | 6         | 0.36%   |
| Taiyo Yuden                     | 4         | 0.24%   |
| Foxconn International           | 4         | 0.24%   |
| Micro Star International        | 3         | 0.18%   |
| Alps Electric                   | 3         | 0.18%   |
| MediaTek                        | 2         | 0.12%   |
| TP-Link                         | 1         | 0.06%   |
| Opticis                         | 1         | 0.06%   |
| Fujitsu Siemens Computers       | 1         | 0.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 329       | 19.98%  |
| Realtek Bluetooth Radio                             | 80        | 4.86%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 79        | 4.8%    |
| Qualcomm Atheros  Bluetooth Device                  | 76        | 4.61%   |
| Ralink RT3290 Bluetooth                             | 67        | 4.07%   |
| Intel AX201 Bluetooth                               | 60        | 3.64%   |
| Dell DW375 Bluetooth Module                         | 41        | 2.49%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 38        | 2.31%   |
| HP Broadcom 2070 Bluetooth Combo                    | 36        | 2.19%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 35        | 2.13%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 35        | 2.13%   |
| Broadcom BCM2045B (BDC-2.1)                         | 35        | 2.13%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 31        | 1.88%   |
| Intel AX200 Bluetooth                               | 29        | 1.76%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 28        | 1.7%    |
| IMC Networks Bluetooth Radio                        | 27        | 1.64%   |
| IMC Networks Bluetooth Device                       | 24        | 1.46%   |
| Broadcom HP Portable SoftSailing                    | 24        | 1.46%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 22        | 1.34%   |
| Realtek RTL8723B Bluetooth                          | 21        | 1.28%   |
| IMC Networks Wireless_Device                        | 21        | 1.28%   |
| Lite-On Bluetooth Device                            | 20        | 1.21%   |
| Foxconn / Hon Hai Bluetooth Device                  | 20        | 1.21%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 19        | 1.15%   |
| Realtek RTL8821A Bluetooth                          | 18        | 1.09%   |
| Realtek  Bluetooth 4.2 Adapter                      | 17        | 1.03%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 16        | 0.97%   |
| Intel Wireless-AC 3168 Bluetooth                    | 16        | 0.97%   |
| Lite-On Atheros AR3012 Bluetooth                    | 15        | 0.91%   |
| Dell BCM20702A0 Bluetooth Module                    | 14        | 0.85%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 14        | 0.85%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 12        | 0.73%   |
| Toshiba Bluetooth Device                            | 11        | 0.67%   |
| Broadcom BCM2070 Bluetooth Device                   | 11        | 0.67%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 10        | 0.61%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 9         | 0.55%   |
| Foxconn / Hon Hai BCM20702A0                        | 9         | 0.55%   |
| Dell Wireless 360 Bluetooth                         | 9         | 0.55%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 9         | 0.55%   |
| Realtek Bluetooth Radio                             | 8         | 0.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1817      | 74.84%  |
| AMD                              | 350       | 14.42%  |
| Nvidia                           | 185       | 7.62%   |
| Silicon Integrated Systems [SiS] | 13        | 0.54%   |
| Logitech                         | 8         | 0.33%   |
| VIA Technologies                 | 7         | 0.29%   |
| C-Media Electronics              | 7         | 0.29%   |
| Lenovo                           | 5         | 0.21%   |
| ASUSTek Computer                 | 5         | 0.21%   |
| Texas Instruments                | 3         | 0.12%   |
| Plantronics                      | 3         | 0.12%   |
| Hewlett-Packard                  | 2         | 0.08%   |
| GN Netcom                        | 2         | 0.08%   |
| Generalplus Technology           | 2         | 0.08%   |
| Creative Technology              | 2         | 0.08%   |
| Apple                            | 2         | 0.08%   |
| Tenx Technology                  | 1         | 0.04%   |
| TEAC                             | 1         | 0.04%   |
| Sony                             | 1         | 0.04%   |
| Sennheiser Communications        | 1         | 0.04%   |
| Samson Technologies              | 1         | 0.04%   |
| Realtek Semiconductor            | 1         | 0.04%   |
| PreSonus Audio Electronics       | 1         | 0.04%   |
| Numark                           | 1         | 0.04%   |
| Kingston Technology              | 1         | 0.04%   |
| Huawei Technologies              | 1         | 0.04%   |
| Focusrite-Novation               | 1         | 0.04%   |
| Corsair                          | 1         | 0.04%   |
| Cooler Master                    | 1         | 0.04%   |
| AudioQuest                       | 1         | 0.04%   |
| AKAI Professional M.I.           | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 224       | 7.62%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 221       | 7.52%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 193       | 6.57%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 155       | 5.28%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 151       | 5.14%   |
| AMD FCH Azalia Controller                                                                         | 112       | 3.81%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 98        | 3.34%   |
| Intel 8 Series HD Audio Controller                                                                | 98        | 3.34%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 97        | 3.3%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 97        | 3.3%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 94        | 3.2%    |
| Intel Broadwell-U Audio Controller                                                                | 92        | 3.13%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 91        | 3.1%    |
| AMD Kabini HDMI/DP Audio                                                                          | 64        | 2.18%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 60        | 2.04%   |
| Intel Cannon Lake PCH cAVS                                                                        | 56        | 1.91%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 55        | 1.87%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 53        | 1.8%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 51        | 1.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 51        | 1.74%   |
| AMD Wrestler HDMI Audio                                                                           | 42        | 1.43%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 40        | 1.36%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 36        | 1.23%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 35        | 1.19%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 33        | 1.12%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 33        | 1.12%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 27        | 0.92%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 27        | 0.92%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 25        | 0.85%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 25        | 0.85%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 24        | 0.82%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 22        | 0.75%   |
| Intel CM238 HD Audio Controller                                                                   | 22        | 0.75%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 20        | 0.68%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 18        | 0.61%   |
| AMD Trinity HDMI Audio Controller                                                                 | 18        | 0.61%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 17        | 0.58%   |
| Nvidia High Definition Audio Controller                                                           | 16        | 0.54%   |
| AMD High Definition Audio Controller                                                              | 16        | 0.54%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 14        | 0.48%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Samsung Electronics   | 557       | 27.16%  |
| SK hynix              | 509       | 24.82%  |
| Kingston              | 227       | 11.07%  |
| Micron Technology     | 214       | 10.43%  |
| Unknown               | 212       | 10.34%  |
| Elpida                | 66        | 3.22%   |
| Nanya Technology      | 63        | 3.07%   |
| Ramaxel Technology    | 44        | 2.15%   |
| A-DATA Technology     | 33        | 1.61%   |
| Crucial               | 26        | 1.27%   |
| Kingmax               | 16        | 0.78%   |
| Corsair               | 9         | 0.44%   |
| ASint Technology      | 9         | 0.44%   |
| Qimonda               | 8         | 0.39%   |
| 48spaces              | 8         | 0.39%   |
| Unknown (ABCD)        | 7         | 0.34%   |
| Transcend             | 6         | 0.29%   |
| Patriot               | 5         | 0.24%   |
| Apacer                | 5         | 0.24%   |
| Toshiba               | 3         | 0.15%   |
| Team                  | 3         | 0.15%   |
| Unknown               | 3         | 0.15%   |
| PUSKILL               | 2         | 0.1%    |
| Melco                 | 2         | 0.1%    |
| Kingmax Semiconductor | 2         | 0.1%    |
| Infineon              | 2         | 0.1%    |
| G.Skill               | 2         | 0.1%    |
| CSX                   | 2         | 0.1%    |
| Unknown (8A5B)        | 1         | 0.05%   |
| Unknown (09D5)        | 1         | 0.05%   |
| Strontium             | 1         | 0.05%   |
| SHARETRONIC           | 1         | 0.05%   |
| Memory Solution       | 1         | 0.05%   |
| Hikvision             | 1         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 43        | 1.95%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 35        | 1.59%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s     | 35        | 1.59%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 32        | 1.45%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 31        | 1.41%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 30        | 1.36%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s             | 29        | 1.32%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s     | 26        | 1.18%   |
| SK hynix RAM HMT325S6CFR8A-PB 2048MB SODIMM DDR3 1600MT/s | 25        | 1.14%   |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s  | 22        | 1%      |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s     | 21        | 0.95%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s     | 21        | 0.95%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 20        | 0.91%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s    | 20        | 0.91%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s     | 20        | 0.91%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s    | 19        | 0.86%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s     | 19        | 0.86%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s     | 18        | 0.82%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s     | 18        | 0.82%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s  | 18        | 0.82%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 17        | 0.77%   |
| Unknown RAM Module 2048MB SODIMM DDR2                     | 16        | 0.73%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 16        | 0.73%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s             | 15        | 0.68%   |
| Unknown RAM Module 1024MB SODIMM DDR2                     | 15        | 0.68%   |
| SK hynix RAM HMT325S6EFR8A-PB 2048MB SODIMM DDR3 1600MT/s | 15        | 0.68%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s    | 14        | 0.64%   |
| Micron RAM 8JSF25664HZ-1G4D1 2GB SODIMM DDR3 1334MT/s     | 12        | 0.55%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s    | 11        | 0.5%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s     | 11        | 0.5%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s     | 11        | 0.5%    |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s      | 11        | 0.5%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s     | 11        | 0.5%    |
| Elpida RAM EBJ21UE8BDS0-DJ-F 2GB SODIMM DDR3 1334MT/s     | 11        | 0.5%    |
| Unknown RAM Module 2048MB SODIMM 800MT/s                  | 10        | 0.45%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s     | 10        | 0.45%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s     | 10        | 0.45%   |
| Nanya RAM NT4GC64B8HG0NS-CG 4GB SODIMM DDR3 1334MT/s      | 10        | 0.45%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s      | 10        | 0.45%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s            | 9         | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 906       | 52.55%  |
| DDR4    | 386       | 22.39%  |
| DDR2    | 222       | 12.88%  |
| SDRAM   | 86        | 4.99%   |
| LPDDR4  | 43        | 2.49%   |
| Unknown | 26        | 1.51%   |
| DDR     | 20        | 1.16%   |
| LPDDR3  | 18        | 1.04%   |
| DRAM    | 8         | 0.46%   |
| DDR5    | 5         | 0.29%   |
| LPDDR5  | 4         | 0.23%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1618      | 96.25%  |
| Row Of Chips | 39        | 2.32%   |
| DIMM         | 15        | 0.89%   |
| Chip         | 8         | 0.48%   |
| Unknown      | 1         | 0.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Notebooks | Percent |
|---------|-----------|---------|
| 4096    | 704       | 37.19%  |
| 2048    | 483       | 25.52%  |
| 8192    | 412       | 21.76%  |
| 1024    | 157       | 8.29%   |
| 16384   | 93        | 4.91%   |
| 32768   | 21        | 1.11%   |
| 512     | 21        | 1.11%   |
| Unknown | 2         | 0.11%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 607       | 32.12%  |
| 2667    | 221       | 11.69%  |
| 1334    | 180       | 9.52%   |
| 667     | 136       | 7.2%    |
| 3200    | 101       | 5.34%   |
| 1333    | 89        | 4.71%   |
| 2400    | 80        | 4.23%   |
| 1067    | 76        | 4.02%   |
| Unknown | 63        | 3.33%   |
| 800     | 56        | 2.96%   |
| 2133    | 47        | 2.49%   |
| 4199    | 43        | 2.28%   |
| 2048    | 33        | 1.75%   |
| 533     | 27        | 1.43%   |
| 975     | 21        | 1.11%   |
| 1066    | 20        | 1.06%   |
| 3266    | 18        | 0.95%   |
| 1867    | 13        | 0.69%   |
| 333     | 10        | 0.53%   |
| 4266    | 8         | 0.42%   |
| 1639    | 8         | 0.42%   |
| 4800    | 6         | 0.32%   |
| 4267    | 5         | 0.26%   |
| 6400    | 4         | 0.21%   |
| 1776    | 4         | 0.21%   |
| 8400    | 3         | 0.16%   |
| 3733    | 2         | 0.11%   |
| 2267    | 2         | 0.11%   |
| 1866    | 2         | 0.11%   |
| 400     | 2         | 0.11%   |
| 2134    | 1         | 0.05%   |
| 1400    | 1         | 0.05%   |
| 200     | 1         | 0.05%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 12        | 52.17%  |
| Samsung Electronics   | 3         | 13.04%  |
| Brother Industries    | 3         | 13.04%  |
| Seiko Epson           | 1         | 4.35%   |
| Ricoh                 | 1         | 4.35%   |
| Oki Data              | 1         | 4.35%   |
| Lexmark International | 1         | 4.35%   |
| Canon                 | 1         | 4.35%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| HP Officejet J4500 series               | 2         | 8.7%    |
| HP DeskJet 2130 series                  | 2         | 8.7%    |
| Seiko Epson XP-240 Series               | 1         | 4.35%   |
| Samsung Xerox Phaser 3117 Laser Printer | 1         | 4.35%   |
| Samsung SCX-4200 series                 | 1         | 4.35%   |
| Samsung Composite Device                | 1         | 4.35%   |
| Ricoh SP 112                            | 1         | 4.35%   |
| Oki Data USB Device                     | 1         | 4.35%   |
| Lexmark International Lexmark X203n     | 1         | 4.35%   |
| HP LaserJet P1102                       | 1         | 4.35%   |
| HP LaserJet P1005                       | 1         | 4.35%   |
| HP LaserJet 1150                        | 1         | 4.35%   |
| HP LaserJet 1022                        | 1         | 4.35%   |
| HP LaserJet 1020                        | 1         | 4.35%   |
| HP LaserJet 1018                        | 1         | 4.35%   |
| HP DeskJet 5550                         | 1         | 4.35%   |
| HP Deskjet 1510                         | 1         | 4.35%   |
| Canon LiDE 400                          | 1         | 4.35%   |
| Brother PTUSB Printing                  | 1         | 4.35%   |
| Brother HL-1110 series                  | 1         | 4.35%   |
| Brother DCP-1610W                       | 1         | 4.35%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                                         | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Canon                                          | 2         | 40%     |
| Siemens Information and Communication Products | 1         | 20%     |
| Mustek Systems                                 | 1         | 20%     |
| KYE Systems (Mouse Systems)                    | 1         | 20%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                           | Notebooks | Percent |
|---------------------------------------------------------------------------------|-----------|---------|
| Siemens Information and Communication Products ID-Mouse with Fingerprint Reader | 1         | 20%     |
| Mustek Systems SNAPSCAN e22                                                     | 1         | 20%     |
| KYE Systems (Mouse Systems) ColorPage-SF600                                     | 1         | 20%     |
| Canon CanoScan LIDE 25                                                          | 1         | 20%     |
| Canon CanoScan 4200F                                                            | 1         | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 511       | 27.58%  |
| IMC Networks                           | 195       | 10.52%  |
| Microdia                               | 169       | 9.12%   |
| Realtek Semiconductor                  | 160       | 8.63%   |
| Sunplus Innovation Technology          | 128       | 6.91%   |
| Suyin                                  | 94        | 5.07%   |
| Quanta                                 | 77        | 4.16%   |
| Bison Electronics                      | 77        | 4.16%   |
| Cheng Uei Precision Industry (Foxlink) | 64        | 3.45%   |
| Syntek                                 | 52        | 2.81%   |
| Acer                                   | 40        | 2.16%   |
| Lite-On Technology                     | 37        | 2%      |
| Silicon Motion                         | 34        | 1.83%   |
| Lenovo                                 | 32        | 1.73%   |
| Alcor Micro                            | 21        | 1.13%   |
| Ricoh                                  | 20        | 1.08%   |
| Primax Electronics                     | 17        | 0.92%   |
| Apple                                  | 17        | 0.92%   |
| Luxvisions Innotech Limited            | 13        | 0.7%    |
| Z-Star Microelectronics                | 11        | 0.59%   |
| ALi                                    | 11        | 0.59%   |
| Logitech                               | 10        | 0.54%   |
| Sonix Technology                       | 9         | 0.49%   |
| Samsung Electronics                    | 9         | 0.49%   |
| Importek                               | 9         | 0.49%   |
| OmniVision Technologies                | 6         | 0.32%   |
| GEMBIRD                                | 5         | 0.27%   |
| icSpring                               | 3         | 0.16%   |
| DigiTech                               | 3         | 0.16%   |
| Colorado                               | 3         | 0.16%   |
| Sunplus Technology                     | 2         | 0.11%   |
| KYE Systems (Mouse Systems)            | 2         | 0.11%   |
| Genesys Logic                          | 2         | 0.11%   |
| Xiaomi                                 | 1         | 0.05%   |
| Spreadtrum Communications              | 1         | 0.05%   |
| Speed Tech                             | 1         | 0.05%   |
| SHENZHEN EMEET TECHNOLOGY              | 1         | 0.05%   |
| MacroSilicon                           | 1         | 0.05%   |
| Holitech                               | 1         | 0.05%   |
| GoPro                                  | 1         | 0.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 61        | 3.28%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 58        | 3.12%   |
| Microdia Integrated_Webcam_HD                 | 47        | 2.53%   |
| IMC Networks USB2.0 HD UVC WebCam             | 44        | 2.37%   |
| Chicony HP Truevision HD                      | 40        | 2.15%   |
| Chicony HD WebCam                             | 38        | 2.05%   |
| Sunplus Integrated_Webcam_HD                  | 35        | 1.88%   |
| Chicony USB2.0 VGA UVC WebCam                 | 30        | 1.62%   |
| Suyin Acer/HP Integrated Webcam [CN0314]      | 25        | 1.35%   |
| Realtek Integrated_Webcam_HD                  | 25        | 1.35%   |
| Microdia Integrated Webcam                    | 25        | 1.35%   |
| Sunplus HP Truevision HD                      | 24        | 1.29%   |
| Chicony Lenovo EasyCamera                     | 24        | 1.29%   |
| Sunplus HD WebCam                             | 23        | 1.24%   |
| Realtek USB Camera                            | 20        | 1.08%   |
| Chicony FJ Camera                             | 20        | 1.08%   |
| IMC Networks Integrated Camera                | 19        | 1.02%   |
| Chicony USB2.0 HD UVC WebCam                  | 19        | 1.02%   |
| Bison Lenovo EasyCamera                       | 19        | 1.02%   |
| Lenovo Integrated Webcam                      | 18        | 0.97%   |
| IMC Networks EasyCamera                       | 18        | 0.97%   |
| Chicony VGA Webcam                            | 18        | 0.97%   |
| Chicony Integrated HP HD Webcam               | 18        | 0.97%   |
| Chicony EasyCamera                            | 18        | 0.97%   |
| Acer Lenovo EasyCamera                        | 18        | 0.97%   |
| Quanta VGA Webcam                             | 17        | 0.92%   |
| Realtek Integrated Webcam                     | 16        | 0.86%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 16        | 0.86%   |
| Bison Integrated Camera                       | 16        | 0.86%   |
| Syntek Lenovo EasyCamera                      | 14        | 0.75%   |
| Realtek Integrated Webcam HD                  | 14        | 0.75%   |
| Microdia Laptop_Integrated_Webcam_HD          | 14        | 0.75%   |
| Lite-On Integrated Camera                     | 14        | 0.75%   |
| Chicony HP Webcam [2 MP Macro]                | 14        | 0.75%   |
| Syntek Integrated Camera                      | 13        | 0.7%    |
| Syntek EasyCamera                             | 13        | 0.7%    |
| Realtek Lenovo EasyCamera                     | 13        | 0.7%    |
| Lenovo Integrated Webcam [R5U877]             | 13        | 0.7%    |
| Bison Lenovo Integrated Webcam                | 12        | 0.65%   |
| Silicon Motion WebCam SC-0311139N             | 11        | 0.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 105       | 37.37%  |
| AuthenTec                          | 56        | 19.93%  |
| Synaptics                          | 33        | 11.74%  |
| Upek                               | 27        | 9.61%   |
| Shenzhen Goodix Technology         | 21        | 7.47%   |
| LighTuning Technology              | 16        | 5.69%   |
| STMicroelectronics                 | 11        | 3.91%   |
| Elan Microelectronics              | 8         | 2.85%   |
| Realtek USB2.0 Finger Print Bridge | 4         | 1.42%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 26        | 9.25%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 26        | 9.25%   |
| AuthenTec AES2810                                                          | 23        | 8.19%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 19        | 6.76%   |
| Shenzhen Goodix  FingerPrint Device                                        | 13        | 4.63%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 12        | 4.27%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 12        | 4.27%   |
| Validity Sensors VFS491                                                    | 11        | 3.91%   |
| STMicroelectronics Fingerprint Reader                                      | 11        | 3.91%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 10        | 3.56%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 9         | 3.2%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 8         | 2.85%   |
| Validity Sensors Synaptics WBDI                                            | 8         | 2.85%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 2.85%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 7         | 2.49%   |
| Shenzhen Goodix Fingerprint Reader                                         | 7         | 2.49%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 6         | 2.14%   |
| LighTuning Fingerprint Reader                                              | 6         | 2.14%   |
| Elan WBF Fingerprint Sensor                                                | 6         | 2.14%   |
| AuthenTec Fingerprint Sensor                                               | 6         | 2.14%   |
| AuthenTec AES1600                                                          | 5         | 1.78%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 1.42%   |
| Synaptics  WBDI                                                            | 4         | 1.42%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 4         | 1.42%   |
| Synaptics Fingerprint reader [HP G6]                                       | 4         | 1.42%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 4         | 1.42%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 3         | 1.07%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 3         | 1.07%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 0.71%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 0.71%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 0.71%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.36%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.36%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.36%   |
| Synaptics WBDI Device                                                      | 1         | 0.36%   |
| Synaptics UWP WBDI Device                                                  | 1         | 0.36%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.36%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.36%   |
| Elan ELAN:Fingerprint                                                      | 1         | 0.36%   |
| Elan ELAN:ARM-M4                                                           | 1         | 0.36%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 122       | 55.71%  |
| Alcor Micro           | 35        | 15.98%  |
| Lenovo                | 29        | 13.24%  |
| O2 Micro              | 26        | 11.87%  |
| Upek                  | 3         | 1.37%   |
| Gemalto (was Gemplus) | 2         | 0.91%   |
| Yubico.com            | 1         | 0.46%   |
| Chicony Electronics   | 1         | 0.46%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 64        | 29.22%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 35        | 15.98%  |
| Lenovo Integrated Smart Card Reader                                          | 29        | 13.24%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 26        | 11.87%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 25        | 11.42%  |
| Broadcom 5880                                                                | 17        | 7.76%   |
| Broadcom 58200                                                               | 15        | 6.85%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 1.37%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.46%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.46%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.46%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.46%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.46%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1427      | 63.79%  |
| 1     | 652       | 29.15%  |
| 2     | 139       | 6.21%   |
| 3     | 15        | 0.67%   |
| 10    | 1         | 0.04%   |
| 7     | 1         | 0.04%   |
| 5     | 1         | 0.04%   |
| 4     | 1         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 280       | 29.2%   |
| Chipcard                 | 204       | 21.27%  |
| Graphics card            | 192       | 20.02%  |
| Bluetooth                | 78        | 8.13%   |
| Net/wireless             | 60        | 6.26%   |
| Storage                  | 37        | 3.86%   |
| Multimedia controller    | 31        | 3.23%   |
| Camera                   | 21        | 2.19%   |
| Flash memory             | 18        | 1.88%   |
| Communication controller | 17        | 1.77%   |
| Sound                    | 6         | 0.63%   |
| Card reader              | 5         | 0.52%   |
| Net/ethernet             | 3         | 0.31%   |
| Network                  | 2         | 0.21%   |
| Modem                    | 2         | 0.21%   |
| Storage/ata              | 1         | 0.1%    |
| Firewire controller      | 1         | 0.1%    |
| Dvb card                 | 1         | 0.1%    |

