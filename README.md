# Open tools for the Nomad Nerd
Curated list of tools and services for the digital nomad and travelling nerd. Including lab gear, mobile equipment and hardware which is researched thoroughly. I own this equipment and have experience with it. Contact via [Twitter](https://twitter.com/audiores), [Reddit](https://www.reddit.com/user/Character_Infamous) or [Medium](https://opengears.medium.com/https://opengears.medium.com/https://opengears.medium.com/). [Please enter additions, suggestions, errors and other things via Github Issues.](https://github.com/z3cko/digital-services/issues)

# Hardware
Overview of hardware suitable for Linux, Mac, and Windows. This is a collection of gear that I own and have reviewed. Criteria for this list: 
* **compatibility**: hardware needs to work with Linux as well as with Mac OS X. Lab equipment should work with [SIGROK](https://sigrok.org/wiki/Main_Page).
* **open**: gear needs to be as open as possible (ideally open-source hardware or fully open repair manuals available).
* **durability**: should be proven long-lasting gear.
* **reparability**: devices should be well-documented and easy to repair.
* **hackability**: devices should be hackable and extensible.
* **mobility**: the gear should be able to be moved around in the world. This sometimes is an oxymoron, but the main focus is on mobile equipment.

You can read my articles on my blog at [opengears.medium.com](https://opengears.medium.com/). The main articles informing this list are:
* [Wi-Fi 6E and Bluetooth 5.3 on Linux: overview of supported dongles and chipsets (M.2, PCIe and USB)](https://medium.com/codex/bluetooth-5-on-linux-overview-of-kernel-supported-dongles-and-chipsets-c6f2b632b236)
* [The Quest for a Good AMD Ryzen Notebook With Linux Support – Winners: Lenovo ThinkPad L14 and L15 (2022 update)](https://medium.com/swlh/the-quest-for-a-good-amd-ryzen-notebook-with-linux-support-winner-lenovo-thinkpad-l15-84a12edf510e)
* [Lenovo L14 AMD G1, G2, G3: which is the better mobile Ryzen choice for 2023? (the answer is not obvious)](https://medium.com/codex/lenovo-l14-amd-g1-vs-gen2-vs-gen3-which-is-the-better-mobile-ryzen-choice-for-2023-3300b0a4055)
* [Open-Source Hardware for a better Future of Repair](https://medium.com/codex/open-source-hardware-for-a-better-future-of-repair-international-repair-day-on-sat-15-october-2022-b0c28af169d6)
* [3 printers with repairable hardware: refurbished hacks and tweaks to optimize the office](https://opengears.medium.com/printer-suggestions-maximum-repairability-refillable-by-design-and-durable-printers-for-home-1dccf31efdc1)
* [Remote office work in the pandemic: document feeders, document scanners, and a few hacks for cheaper solutions for digitization](https://opengears.medium.com/remote-office-work-in-the-pandemic-document-feeders-document-scanners-and-a-few-hacks-for-2b285c22f7e1)

# Table of contents
- [Open tools for the Nomad Nerd](#open-tools-for-the-nomad-nerd)
- [Hardware](#hardware)
- [Table of contents](#table-of-contents)
- [Tools for repairing, modding, and building](#tools-for-repairing--modding--and-building)
  * [Lab devices](#lab-devices)
    + [Power supply](#power-supply)
    + [Oscilloscopes](#oscilloscopes)
  * [Repair tools](#repair-tools)
  * [Notebooks](#notebooks)
    + [GNUboot and Libreboot compatible devices](#gnuboot-and-libreboot-compatible-devices)
    + [ARM and RISC-V](#arm-and-risc-v)
    + [Non-Libre (but still good)](#non-libre--but-still-good-)
  * [SSDs and HDDs](#ssds-and-hdds)
  * [Chargers](#chargers)
  * [Mobile phones and tablets](#mobile-phones-and-tablets)
- [Wireless](#wireless)
  * [Wi-Fi 6E and Bluetooth 5.4](#wi-fi-6e-and-bluetooth-54)
  * [Libre wireless routers](#libre-wireless-routers)
    + [OpenWRT compatible routers](#openwrt-compatible-routers)
    + [LibreCMC (de-blobbed libre Linux)](#librecmc--de-blobbed-libre-linux-)
- [Computer gear](#computer-gear)
    + [Keyboards](#keyboards)
    + [Mice and Trackpads (HID)](#mice-and-trackpads--hid-)
  * [Printers](#printers)
    + [dot matrix](#dot-matrix)
    + [Inkjet](#inkjet)
    + [Laser](#laser)
  * [Scanners](#scanners)
  * [Video and recording](#video-and-recording)
  * [Cameras](#cameras)
  * [HDMI capture](#hdmi-capture)
  * [Sound](#sound)
    + [Soundcards](#soundcards)
    + [Microphones](#microphones)
    + [Headsets](#headsets)
- [Services and talent](#services-and-talent)
  * [Cloud services and hosting](#cloud-services-and-hosting)
  * [Freelancers, talent and remote work](#freelancers--talent-and-remote-work)
- [Banking, trading and crypto](#banking--trading-and-crypto)
  * [Market analytics](#market-analytics)
  * [Bank Accounts for perpetual travelers and digital nomads](#bank-accounts-for-perpetual-travelers-and-digital-nomads)
  * [Cryptocurrency](#cryptocurrency)
    + [Digital Currency Exchanges](#digital-currency-exchanges)
- [Cybersecurity and Cryptography](#cybersecurity-and-cryptography)
  * [Privacy-aware notebooks](#privacy-aware-notebooks)
  * [TRNG hardware random number generators](#trng-hardware-random-number-generators)
  * [2FA and hardware security](#2fa-and-hardware-security)

# Tools for repairing, modding, and building

## Lab devices
### Power supply
* DPS3005 based
  * [DPS3005 Programmable Power Supply](https://amzn.to/3Tsr22B) - variable power supply available for less than $50 with a good set of features. Read background on [hackaday](https://hackaday.com/blog/?s=DPS3005). See also: [DollaTek Cold-Rolled Steel Material DIY Housing Kit for DPS Series](https://amzn.to/3zcRxRC) - enclosure for the DPS3005
  * [KORAD KA3005P](https://amzn.to/3Tys6St) - Programmable Precision Variable Adjustable 30V, 5A DC Linear Power Supply
* [RIGOL DP832A](https://amzn.to/3YpEms7) - excellent (but more premium) lab power supply. supports sigrok. 
### Oscilloscopes
  * [Hantek 6022BE Oscilloscope](https://amzn.to/3C4XIvk)
  * [Rigol DS1054Z 4CH 50MHz Digital Oscilloscope](https://amzn.to/3NMXX0s)
  * Rigol MSO5074
## Repair tools
* [Klein Tools 32500](https://amzn.to/3f36WNl) - 11-in-1 Screwdriver / Nut Driver Set, 8 Bits (Phillips, Slotted, Torx, Square), 3 Nut Driver Sizes, Cushion Grip Handle 
* [Klein Tools 32717](https://amzn.to/3W0NLEF) - precision screwdriver set with case, all-in-one multi-function repair tool kit includes 39 bits for apple products
* [iFixit Jimmy bundle](https://amzn.to/3zexfXQ) - iFixit Jimmy + Prying and Opening Tool Assortment Bundle
* [PINECIL Smart Mini Portable Soldering Iron](https://pine64.com/product/pinecil-smart-mini-portable-soldering-iron/) - pinecil is a small soldering iron with a RISC-V Bouffalo BL-706, USB-C.

## Notebooks
### GNUboot and Libreboot compatible devices
* [Lenovo X200 Laptop – FSF RYF certified](https://shop.vikings.net/product/vikings-x200-laptop/?v=471c1f3fc1dd) hardened high-security Laptop without Intel ME
* [Lenovo X230](https://shop.vikings.net/product/x230/?v=471c1f3fc1dd#cpu)
* [Lenovo T440p Laptop](https://shop.vikings.net/product/t440p/?v=471c1f3fc1dd)
* [Lenovo W530](https://amzn.to/4fnhuAC) with up to 32GB RAM. Works with Libreboot and runs Qubes OS.

### ARM and RISC-V
* MNT Reform, MNT Pocket Reform
* [DC-ROMA RISC-V Laptop II](https://amzn.to/40kqdzd)

### Non-Libre (but still good)
* [Lenovo Thinkpad L14 AMD (Gen1, Gen2 or Gen3)](https://amzn.to/3LVQxoC) - the perfect Linux notebook. A perfect way to upcycle is [buying the L14 or L15 AMD Ryzen second-hand](https://ebay.us/LMXg1S). Read this [comparison of the Lenovo Thinkpad Gen1 vs Gen2 vs Gen3](https://medium.com/p/3300b0a4055).
* [ASUS ROG Strix G15 AMD](https://amzn.to/3z7YyTL) - high performance Linux workstation, with support for Ryzen 9 and 5900HX and Ryzen 9 6900HX. Upgradeable to 64GB RAM. Read the [notes on Reddit](https://www.reddit.com/r/linux_gaming/comments/nb9jw5/linux_on_the_asus_rog_strix_g15/)
* [HP EliteBook 865 G10, Ryzen](https://amzn.to/442NYua) - The HP Elite Book 865 G10 is available with AMD Ryzen 7540U, 7840U, and 7940HS. It features two (!) USB4 ports, a 1000cd/​m² bright screen, and has a maximum of 64GB RAM. 
* [ASUS TUF Gaming Advantage A16](https://amzn.to/3XqmhcB) - Ryzen 9 7940HS ZEN4, DDR5, Radeon RX 7600S with Navi 33 LE (see [Asus product page](https://www.asus.com/de/laptops/for-gaming/tuf-gaming/asus-tuf-gaming-a16-advantage-edition-2023/)). 2x 

## SSDs and HDDs
*  Western Digital WD_BLACK SN850X NVMe SSD 8TB, M.2 2280 / M-Key / PCIe 4.0 x4
*  Toshiba Cloud-Scale Capacity MG10F AFA 22TB, 24/7, 512e/4Kn / 3.5" / SATA 6Gb/s (MG10AFA22TE)

## Chargers
* [Anker PowerPort III with PPS Fast Charger Adapter](https://amzn.to/3svfpfA) - 65W USB-C charger with Power Delivery and 3-Port PPS Fast Charger
* [Razer USB-C 130W GaN Charger ](https://amzn.to/3gGtap1) - PD 3.0 130W charger with global compatibility (UK, EU, US)
* [Amazon Basics 68W Two-Port GaN USB-C Wall Charger (50W + 18W)](https://amzn.to/3Fj5d19) - cheap PD 3.0 69W charger

## Mobile phones and tablets
* [OnePlus 6 (oneplus-enchilada)](https://wiki.postmarketos.org/wiki/OnePlus_6_(oneplus-enchilada))
* [Hardened Google Pixel 6](https://ebay.us/N1S3Xm) - make sure to install CalyxOS or GrapheneOS.
* [PinePhone Linux Phone](https://ebay.us/zuSgE3) - Quad-Core Allwinner A64 @ 1.152 GHz; you can [get more information at the Pine64 website](https://www.pine64.org/pinephone/)

# Wireless

## Wi-Fi 6E and Bluetooth 5.4
* [Wi-Fi 4 (802.11n), 2.4/5GHz, Atheros QCNFA222 AR9462, Bluetooth 4.0, M.2/NGFF](https://shop.vikings.net/product/wi-fi-4-802-11n-2-4-5ghz-atheros-qcnfa222-ar9462-bluetooth-4-0-m-2-ngff/?v=471c1f3fc1dd)
* [**Intel AX210NGW** (NGFF M2 2230 A/E key) with WiFi (6GHz, 5GHz and 2.4GHz) and Bluetooth 5.3](https://ebay.us/noiceB) - the only recommendable NGFF Wi-Fi 6E + Bluetooth 5.3 adapter that works for notebooks and desktops and is fully Linux supported.
* [NGFF (M.2) to PCI-E 1X adapter](https://ebay.us/rr6yDD) - if you need a PCIe adapter to mount NGFF in you desktop
* [**Edimax BT-8500**](https://www.edimax.com/edimax/merchandise/merchandise_detail/data/edimax/global/bluetooth/bt-8500/) - Bluetooth 5 USB dongle (RTL8761B) [working since Kernel 5.8 with A2DP and HSP/HFP](https://www.reddit.com/r/linux/comments/qymjpl/edimax_bt8500_usb_blueooth_50_that_works/).

## Libre wireless routers
Wireless routers which are compatible with [LibreCMC](https://librecmc.org/) and [OpenWRT](https://openwrt.org/). 

### OpenWRT compatible routers
* [Turris Omnia](https://amzn.to/3LIg9pG) - fantastic Open Source router with 2GB RAM.
* [TP-Link TL-WR1043ND](https://ebay.us/4ewRo2)
* [Linksys WRT3200ACM](https://ebay.us/j4R1g0)

### LibreCMC (de-blobbed libre Linux)
* [Netgear WNDR3800](https://ebay.us/QHAxwu)
* [TP-Link TL-WR842ND](https://ebay.us/Sangcf)
* [TP-Link TL-WR1043ND](https://ebay.us/4ewRo2)


# Computer gear
### Keyboards
* [MoErgo Glove80](https://www.moergo.com/products/glove80-split-ergonomic-keyboard-revision-2)
* [Keychron C2 Full Size Mechanical Keyboard](https://amzn.to/3Tr2rLG)
* [Durgod Taurus K320 TKL Mechanical Keyboard)](https://amzn.to/3KvYVuP) - Double Shot PBT, USB Type C, Cherry Brown switches
* [ZSA Moonlander](https://www.zsa.io/moonlander/) and the [ErgoDox FT](https://falba.tech/customize-your-keyboard/customize-your-ergodox/) are excellent ergonomic split keyboards.
* [HHKB Happy Hacking Keyboards](https://ebay.us/qltUzC) - Topre switches, collector's items Japanese quality keyboards for enthusiasts.

### Mice and Trackpads (HID)
* [ploopy](https://ploopy.co/mouse/) ploopy creates mice and trackballs which are fully customizable and run QMK.
* [Logitech MX Master 3 Advanced Wireless Mouse](https://amzn.to/3unwsBU) - bluetooth mouse for Linux, Mac, Win, Android and iOS (Linux support via [Solaar](https://github.com/pwr-Solaar/Solaar))
* [Razer DeathAdder Essential Gaming Mouse](https://amzn.to/3up5RV8) - Razer gaming mouse with full Linux support (Linux support via [openrazer](https://github.com/openrazer/openrazer/))
* [Apple Magic Trackpad 2 (2022)](https://amzn.to/3M5aJYp) - the Apple Magic Trackpad works on Linux, but you have to [tweak the xinput configuration](https://superuser.com/questions/1705684/does-the-apple-magic-trackpad-2-work-on-linux)

## Printers
### dot matrix
* 
### Inkjet
* [Epson EcoTank ET-2750](https://ebay.us/rGc0bg)

### Laser
* [Hewlett Packard HP LaserJet 4](https://ebay.us/6eOpcz) - a classic. If you can afford it and you can get your hands on one, this will last for decades.
* [Brother HL-2030](https://t.co/eViUoj6gPp) - hard to find, but definitely one of the best printers to get spare parts and maintainance materials for. 2400x600dpi.
* [Brother HL-L5100DN](https://ebay.us/EBpS0o)
* [Brother HL-1110](https://ebay.us/v5sLV9) - this one is only a bargain if used with [Brother HL-1110 compatible toners and drums](https://ebay.us/v5sLV9)
* [Kyocera FS-1118MFP](https://ebay.us/sYyXnR) - great printer with cheap price-per-page. [Works perfeclty with PPD on Linux and Mac OS](https://www.openprinting.org/printer/Kyocera/Kyocera-FS-1118MFP)

## Scanners
* [Fujitsu fi-8150](https://amzn.to/3LEf0iD)
* [Fujitsu ScanSnap Series](https://ebay.us/VssEue)
* [Epson B11B265401 WorkForce DS-790WN](https://amzn.to/3F4t42u)

## Video and recording

## Cameras
* [Sony A7 (ILCE-7)](https://ebay.us/t9JyPO) - the Sony A7 (and the A7 II, as well as subsequent models) have clean HDMI output. These are the best possible "webcams" in case you are an influencer or want the best possible video recording for your Linux or Mac OS X machine.

## HDMI capture
* [HDMI Video Capture Card USB-C, 4K](https://amzn.to/3M8qn25) - 4K/1080 60 FPS capture card that works with Linux and Mac OSX.
* [Rybozen 4K Audio Video Capture Card, USB 3.0 HDMI Video Capture Device](https://amzn.to/3ybgr4g) - 4K or 1080p HDMI capture card for DSLR or consoles confirmed to work with Linux and Mac OS X out of the box.

## Sound

### Soundcards
* [Focusrite Scarlett Solo 3rd Gen USB Audio Interface](https://amzn.to/3jm0CPt)
* [ASUS Xonar DX 7.1, PCIe x1 (90-YAA060–1UAN00Z)](https://ebay.us/kHExTI)
* [Native Instruments Audio 8 DJ USB](https://ebay.us/XFMiU9) - 8 inputs, 8 outputs. Toggleable phono preamps on 4 inputs. Any Linux build with Kernel 2.6.22 will support the Audio 8 DJ natively ([source](https://www.native-instruments.com/forum/threads/audio-8-linux-support.56382/)).

### Microphones
* [SHURE MV7 motiv podcasting microphone USB+XLR](https://amzn.to/3eX8KHK)
* [SHURE XLR microphones](https://ebay.us/RHISva)

### Headsets
* [Cooler Master MH630](https://amzn.to/3SuBvJz) is a very affordable and excellent headset, for $45! The microphone sounds great, even beating more expensive options.
* [Beyerdynamic DT-770 Pro](https://ebay.us/3bkW9C) - the reference headset in 32, 80 and 250 Ohms
* [Austrian Audio Hi-X25BT Professional Closed-Back Bluetooth Headphones](https://ebay.us/DXiAHD) - great headset with Bluetooth, USB-C (digital), analogue (3.5mm headphone jack) and included microphone
* [HP HyperX Cloud Orbit S ](https://ebay.us/Wm02yl) - confirmed to work with Linux [Pipewire and Pulseaudio](https://www.reddit.com/r/linuxhardware/comments/o9hwr1/suggested_headset_with_superior_sound_and_wired/)

# Services and talent

## Cloud services and hosting
* [$20 coupon for Hetzner Cloud](https://hetzner.cloud/?ref=IqAaoRsf4wVN)

## Freelancers, talent and remote work
* [$100 coupon for Fiverr](http://www.fiverr.com/s2/46ef8ec9e7)

# Banking, trading and crypto

## Market analytics
* [Tradingview](https://www.tradingview.com/gopro/?share_your_love=audioreservoir) - here is a $30 coupon for TradingView

## Bank Accounts for perpetual travelers and digital nomads
* [Revolut](https://revolut.com/referral/matthilu1) $50 signup discount for Revolut Bank
* [Wirex](https://wirexapp.com/r/rdncecnm2u) - great Fiat<>Crypto service based in the UK. Available for EU banking (including Visa card)

## Cryptocurrency

### Digital Currency Exchanges

* [Binance Exchange](https://www.binance.com/en/register?ref=Q93IAC37)
* [Bitfinex](https://www.bitfinex.com/sign-up?refcode=19-lHYAit) - good and solid centralized exchange
* [Poloniex Crypto exchange](https://poloniex.com/signup?c=Z8MM6FB6)

# Cybersecurity and Cryptography

## Privacy-aware notebooks
* [Minifree](https://minifree.org/) - secure high-qualiy modded Lenovo T440p, X230 with osboot (based on coreboot) and 5 years of warranty
* [NitroPad](https://www.nitrokey.com/news/2020/nitropad-secure-laptop-unique-tamper-detection) - Secure Laptop With Unique Tamper Detection (ThinkPad X230)
* [Vikings RYF Respects Your Freedom Notebooks](https://store.vikings.net/en/ryf) - these are excellent devices such as X200. The T440, the X230 and others are listed as "libre-friendly laptops".  

## TRNG hardware random number generators
* [ubld.it TrueRNG V3](https://amzn.to/3VXjsii) - USB Hardware Random Number Generator.
* [OneRNG](https://onerng.info/) - Open Hardware Random Number Generator.
* [Altus Metrum/ ChaosKey](https://altusmetrum.org/ChaosKey/) - a hardware True Random Number Generator that attaches via USB.

## 2FA and hardware security
* [Nitrokey](https://www.nitrokey.com/#comparison) - Open Source Hardware 2FA and key storage
* [Trezor Hardware Wallet](https://trezor.go2cloud.org/aff_c?offer_id=133&aff_id=6069) - Open Source Hardware cryptocurrency wallet
* [Ledger Hardware Wallet](https://shop.ledger.com?r=eb1e)
  * [Ledger Nano-S Plus](https://shop.ledger.com/pages/ledger-nano-s-plus?r=eb1e)
