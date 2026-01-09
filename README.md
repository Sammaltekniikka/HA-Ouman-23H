# HA-Oman-23H

Home Assistant integration for Ouman H23 heating controller using Modbus RTU/TCP via Waveshare RS485 to ETH.

## Hardware
- **Server:** Dell OptiPlex 7050
- **Controller:** Ouman H23
- **Gateway:** Waveshare RS485 to RJ45 Ethernet Converter

## Documentation
- **Modbus Map:** Detailed register map is available in this repository as `Ouman_H23_Modbus_Map.pdf`. 
- **Config:** See `ouman_h23.yaml` for Home Assistant sensor configurations.

## Connection Settings
- **IP Address:** 192.168.x.x (Replace with your actual Waveshare IP)
- **Port:** 502
- **Modbus Slave ID:** 1

## Project Status
- [ ] Install Waveshare adapter (Scheduled: Jan 10-11)
- [ ] Upload Modbus PDF map to repository
- [ ] Configure Modbus sensors in Home Assistant
- [ ] Verify data accuracy from Ouman H23
