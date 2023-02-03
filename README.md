# credit-card-reader

Easy reading on credit cards over PC/SC or NFC with Node.js

## Requirements

[Node.js >= v12](https://nodejs.org/)

For Debian/Ubuntu users, you must also install this packages:

```
apt-get install libpcsclite1 libpcsclite-dev pcscd
```

On MacOS, PC/SC is already installed.

## Hardware requirements

[Feitian Contact smart card reader R301]([https://amzn.to/3caTTV](https://www.alibaba.com/product-detail/Contact-IC-Chip-USB-Smart-Card_62090500846.html?spm=a2700.galleryofferlist.normal_offer.d_title.65f37d55XQMIL8))

[Feitian NFC smard card reader R502](https://www.alibaba.com/product-detail/Access-RFID-Card-Reader-Contactless-NFC_62090650304.html?spm=a2700.shop_plgr.41413.25.5d463ab1IYruQV)

## Getting Started

To get started, first install all the necessary dependencies.

```
npm install
```

## Get data from card by chip

```
node src/chip.js
```

## Get data from card by NFC

```
node src/nfc.js
```

## HackRF (WIP)

```
node src/hackrf.js
```
