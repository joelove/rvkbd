
## Version 1 Build Guide

### Required Components

Below is listed the minimum components required to assemble a single keyboard.

> It's important to have spares for if you make a mistake. Also, buying more units of a component gets much cheaper very quickly so don't be afraid to buy more than you need or aim to build two.

| | Component | Link |
|-|-----------|------|
| 2 | Raven keyboard PCBs | [Download Gerber](raven-split-38key/raven-split-38key__choc-hotswap-n!n/pcb/gerber.zip  "download") |
| 2 | Raven keyboard plates (1.2mm) | [Download Gerber](raven-split-38key/raven-split-38key__choc-hotswap-n!n/pcb/gerber.zip "download") |
| 2 | Compatible wireless microcontrollers | [Buy NRF52840 Supermini](https://www.aliexpress.com/w/wholesale-NRF52840-Supermini.html) <br> [Buy nice!nano v2](https://nicekeyboards.com/nice-nano) |
| 2 | 3x6 DIP TS-1136 reset button | [Buy TS-1136 DIP reset button](https://www.aliexpress.com/w/wholesale-TS%2525252d1136-DIP-button.html) |
| 2 | MSK-12C02 7-pin SMD power switch | [Buy MSK-12C02 power switch](https://www.aliexpress.com/w/wholesale-MSK%2525252d12C02-7%2525252dpin-SMD-toggle-switch.htmlf) |
| 36 | Kailh Choc (v1) switches | [Buy Choc (v1) switches](https://lowprokb.ca/collections/switches/products/sunset-tactile-choc-switches) |
| 36 | Choc low profile hot swap sockets | [Buy Choc (v1) hot swap sockets](https://www.kailhswitch.com/mechanical-keyboard-switches/box-switches/choc-type-hot-swap-socket.html) |
| 36 | 1N4148 SOD-123 SMD diodes | [Buy 1N4148 SMD diodes](https://www.aliexpress.com/w/wholesale-1N4148-SOD%2525252d123-SMD-diode.html) |
| 30 | 1u Chosfox low profile PBT keycaps | [Buy 1u keycaps](https://www.aliexpress.com/item/1005004558099208.html) |
| 4 | 1.5u Chosfox low profile PBT keycaps | [Buy 1.5u keycaps](https://www.aliexpress.com/item/1005004780019538.html) |
| 2 | 1u Chosfox homing keys | [Buy 1u homing keys](https://www.aliexpress.com/item/1005004780019538.html) |

> The Chosfox keycaps are 17x17mm and the key spacing on the PCB has been designed with that spacing in mind. I've read that the standard Kailh keycaps are is 1mm wider so it's probably wise to use these exact keycaps (unless you know what you're doing)

### Optional Components

You might want extra, optional components for socketing or adding a cover to the microcontroller, adding rubber feet or other details. I've included a separate list of those items here and their purposes to help you choose.

| | Component | Reason |
|-|-----------|--------|
| 4 | 12-pin female sockets | Socketing the microcontroller means it can be replaced if it breaks or you make a mistake installing it. Without sockets, an issue like that might require a full rebuild or difficult de-soldering job. There are a few different options but I use the lowest profile variety and cut the legs off thru-hole diodes to serve as male pins from the PCB. |
| 4 to 60 | 2mm+ sticky rubber feet | Without a case, adding rubber feet directly to the bottom of the PCB stops it moving around on the table. The more feet the better because it adds weight, protects the components underneath and allows it to sit stable on less flat surfaces. |
| 2 | 2–3mm acrylic covers | Adding covers to the microcontroller hides them and provides protection. I manually fabricated my own but you could lazer cut the required shape. I haven't yet created a DXF for that component but may in the future. |
| 4 | M2 8mm stand-offs | To hold the cover the correct distance from the PCB, small double-sided stand-offs are needed. With the low profile sockets, I needed 6 or 8mm long stand-offs, but that will vary based on exactly how you solder the microcontroller. |
| 8 | M2 6mm wafer head bolts | Attaching the stand-offs needs flat wafer bolts, both to reduce protrusion on the underside and also to avoid cracking the acrylic covers. DO NOT over-tighten! |
