# 🍬 sweetbit

>A Bitcoin-based candy dispenser.

![bitcoin candy dispenser](https://user-images.githubusercontent.com/198988/40588423-72ae6898-61dd-11e8-8921-fbb9e948552b.gif)

* A [touch-enabled candy dispenser](https://www.amazon.de/gp/product/B01M15MVNY/ref=oh_aui_detailpage_o00_s00?ie=UTF8&psc=1)
* All electronics exchanged
* Arduino Micro added to make things controllable through USB
* A Go tool that listens to transactions and controls the dispenser

```
sweetbit \
  --debug.dispense 0.5s \
  --device.path /dev/tty.usbmodem1411 \
  --device.pin 3 \
  --bitcoin.address 35cqbbBap7trDfb18YExSBjaN8rTQ8CmhL \
  --lightning.subscription wss://the.testnet.lightning.land/candy/graphql
```
