# lidar-pcb

Released versions of the LIDAR PCBs and parts lists. Everything that's necessary to order PCBs from https://jlcpcb.com

There are two PCB designs stored here:
- **scanner** is the main PCB with all the electronics required to run the scanner: https://oshwlab.com/dvoros/scanner
- **scanner-power-supply** is the small PCB with the power plug that's embedded in the scanner's base station: https://oshwlab.com/dvoros/scanner-power-supply

## Design guidelines

What I kept in mind:
- Simplicity: easy to solder parts, not going for miniatures.
- Availability: all components were picked from JLCPCB parts so they can be ordered together (and assembled) with the PCB. I was trying to pick the most popular (most pieces in stock) items and avoid discontinued products.
- Price and waste: I'm trying to balance between price and minimum order quantity so people who need a single PCB won't end up with hundreds of unwanted parts.

## Notes for releasing a new version

In EasyEDA:

- Don't forget to rebuild copper area!
- Clone the PCB to serve as the new "vX-next"
- Rename the PCB to include the date
- Update the texts on the PCB that include the version and the date
- Export Gerber+BOM+Pick-and-Place and save them in this repo
- Download whole project and save in this repo

## Contribution

All contributions are welcome! Feel free to open a Github issue here or comment on the design at OSHW.