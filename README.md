# pippin
Pippin or Pi Pen is a collection of resources for security analysis and penetration testing for the Raspberry Pi

There are many projects that use ESP32 and devices like Flipper that bring together multiple pieces of hardware with a nice interface but I still think there is a place for SBC like a Raspberry PI that can run a full linux os and take advantage of both USB and gpio to expand hardware functionality.

## Projects

### PWNAGOTCHI

[Pwnagotchi](https://pwnagotchi.ai/) is an A2C-based “AI” powered by bettercap and running on a Raspberry Pi Zero W that learns from its surrounding WiFi environment in order to maximize the crackable WPA key material it captures (either through passive sniffing or by performing deauthentication and association attacks). This material is collected on disk as PCAP files containing any form of handshake supported by hashcat, including full and half WPA handshakes as well as PMKIDs.


## Hardware
### nRF24 

The NRF24 is a popular line of 2.4GHz radio transceivers from Nordic Semiconductors.

[nRF24LU1+](https://github.com/BastilleResearch/nrf-research-firmware)

### CC1101

The CC1101 is a low-cost sub-1 GHz transceiver designed for very low-power wireless applications. The circuit is mainly intended for the ISM (Industrial, cientific and Medical) and SRD (Short Range Device) frequency bands at 315, 433, 868, and 915 MHz, but can easily be programmed for operation at other frequencies in the 300-348 MHz, 387-464 MHz and 779-928 MHz bands.

[CC1101 on Amazon](https://www.amazon.com/K0R41-CC1101-Frequency-Transceiver-Module/dp/B0C8RRG88V/ref=sr_1_2?dib=eyJ2IjoiMSJ9.S0vz2ophvs_UouDmIwfvX-SapMsyC1kC6-Te3K3VMRiEmtuT-zmjIV7JijMyPu_NXPvOcuVMP-adZyDNo_pwQLZeEXmd8HhmFS2_3u7FMbRrThySvhkbcAQBmah00ruD1XlaMoOBVTi3xSDe2Ib95Uz0cWLbBRwbNoSYRmSopmAjhWlVwESsQhwaPxHJGKgvGkZkrAesyWYic8NCNcxKdPp7fsWRP-a3y5l8g9wL-Iw.PDUuzT5gAzddmQSS9CW_ZkkMvFcKNGv7Dq6ZcB7lVUI&dib_tag=se&hvadid=557479865405&hvdev=c&hvlocphy=9051962&hvnetw=g&hvqmt=e&hvrand=16315026679325655135&hvtargid=kwd-47345189796&hydadcr=17954_13446725&keywords=cc1101+transceiver&qid=1715878123&sr=8-2)

### PN532

The PN532 is a highly integrated transceiver module for contactless communication at 13.56 MHz based on the 80C51 microcontroller core supporting different card and reader/writer operating modes.

[PN532 NFC NXP RFID Module](https://www.amazon.com/HiLetgo-Communication-Arduino-Raspberry-Android/dp/B01I1J17LC/ref=sr_1_2_sspa?crid=3CHFHCXOOYXSB&dib=eyJ2IjoiMSJ9.Siw_ZMmtUYTICaz3qXNzjINLkahg00ZmcxC12LA0ETnxjy1NsfKx-a5BkFqVN66zQYgPnypTXlXEemQWv6su9J-NID6qWHjhQYA_D0P9f-B-3ilUFZnz4ov8I-dRU1mOxj7QPsaLtrRLjBRD70c8A7yr430y0hlQIU0IPM0m4ASjKubeKMZ1vspqlZjTce5Z7uyV2t-i78glip4e1BZKnnQHngbdDSzAAuRTt4z_ltE.KtJDWq0Pz6EPdg2PiPdGU-gj1p6jQ0xGMnjOD4Qdb2g&dib_tag=se&keywords=PN532&qid=1715878275&sprefix=pn532%2Caps%2C98&sr=8-2-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1)

## Software

### Linux Distros
[Raspberry Pi OS](https://www.raspberrypi.com/software/operating-systems/) - Full linux desktop or lite base image
[Kali Linux](https://www.kali.org/get-kali/) - Popular linux distro with most popular tools already installed and organized

### Mousejacking

[jackit](https://github.com/insecurityofthings/jackit) - see [nRF24](#nrf24)

### Bad USB/ Duckyscript

The USB Rubber Ducky is a Human Interface Device programmable with a simple scripting language allowing penetration testers to quickly and easily craft and deploy security auditing payloads that mimic human keyboard input.

[Duckberry-Pi](https://github.com/ossiozac/Raspberry-Pi-Zero-Rubber-Ducky-Duckberry-Pi)

### Captive Portal / Evil Twin

[Evil-AP](https://github.com/MohammedRaouf99/Evil-AP)

[Evil-Twin-tool](https://github.com/vection/Evil-Twin-tool)

[Rudrastra](https://github.com/vrikodar/Rudrastra)

[PiEvilTwin](https://github.com/NickJongens/PiEvilTwin)

### Rogue AP see [Captive Portal / Evil Twin](#captive-portal--evil-twin)

[rpihotspot](https://github.com/idev1/rpihotspot)

