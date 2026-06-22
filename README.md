## Status

  **RevA** In development (schematic complete, layout pending)

## Key Components

| Function | IC | Notes |
|----------|----|----|
| Charger | BQ24074 | USB100/500 + ILIM modes |
| Protection | BQ29728 | OCP/OVP/UVP |
| Fuel Gauge | BQ27427 | Coulomb counter |
| Buck-Boost | TPS63020 | ~1.8-5.5V input, 3.3V/5V output |
| MCU (Smart) | ATtiny3217 | CAN interface logic |
| CAN Controller | MCP2515 | SPI interface |
| CAN Transceiver | SN65HVD230 | ISO11898-2 compliant |

## Usage

Battery powered 5w power supply for projects that use 3v3 or 5v.
The smart version tracks system status and communicates over CAN bus.

## Known Issues / TODOs

- [ ] PCB layout and thermal analysis
- [ ] Publish assembly guide and test procedure

## License

CC0 
