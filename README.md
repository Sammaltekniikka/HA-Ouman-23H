# HA-Oman-23H

Home Assistant integration for Ouman H23 heating controller using Modbus RTU/TCP via Waveshare RS485 to ETH.

## Hardware
- **Controller:** Ouman H23
- **Gateway:** Waveshare RS485 to RJ45 Ethernet Converter

## Documentation
- **Modbus Map:** Detailed register map is available in this repository as `Ouman_H23_Modbus_2021.pdf`. 
- **Config:** See `ouman_h23.yaml` for Home Assistant sensor configurations.

## Connection Settings
- **IP Address:** 192.168.x.x (Replace with your actual Waveshare IP)
- **Port:** 502
- **Modbus Slave ID:** 1

## Project Status
- [X] Install Waveshare adapter
- [X] Upload Modbus PDF map to repository
- [X] Configure Modbus sensors in Home Assistant
- [X] Verify data accuracy from Ouman H23


# Ouman 23H Modbus-integraatio (Vuosimalli 2021)

Tämä projekti sisältää Modbus-rekisterilistan ja Home Assistant -konfiguraation **Ouman 23H -säätimelle**, jonka laiteversio on **2.0.1 (vuosimalli 2021)**.

## ⚠️ Tärkeä huomautus yhteensopivuudesta
Tässä repositoriossa oleva rekisterilista on testattu toimivaksi vuoden 2021 mallilla.
* **Jos laitteesi on uudempi:** Rekisteriosoitteet ovat todennäköisesti muuttuneet. 
* **Uusimmat listat:** Tarkista [Oumanin lataussivu](https://ouman.fi/downloads/) tai ota yhteys Oumanin huoltoon.

## Sisältö
* `Ouman_23H_Modbus_2021.pdf`: Itse koottu rekisterilista (Holding-rekisterit, S32-formaatti).
* `configuration.yaml`: Esimerkkikonfiguraatio Home Assistantiin.

## Tekniset tiedot
Kaikki arvot ovat **holding-rekistereitä** ja käyttävät **S32-osoitemuotoa** (32-bittinen etumerkkinen kokonaisluku). Lämpötila-arvoissa on yksi desimaali (scale: 0.1).

## Youtube video
https://youtu.be/izNtwWvsyh4
Videolla käydään Waveshare RS485 POE Modbuys gateway asennus ja HomeAssistantin ohjelmointi.
