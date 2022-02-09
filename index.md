# tinc.cloud
AlsLUG's VPN-netværk

## Generelt
tinc.cloud er basseret på [tinc](https://www.tinc-vpn.org/) som er et open-source distriburert VPN-netværk.

Fordelen ved at bruge tinc i stedet for fx OpenVPN er at vi ikke er afhængige af en central server. Hverken til authentication eller til at route trafikken.

- hvis du har adgang til bare en enkelt af de offentlige servere, har du som udgangspunkt adgang til alle services.
- alle kan som udgangspunkt kommunikere med alle. Med et lille trick kan adgangen til en enhed begrænses til kun at tillade bestemte enheder.
- kommunikationen i netværket kører peer-to-peer, så trafikken mellem fx din telefon og din nextcloud-server hjemme i kosteskabet kører ikke gennem central servere.

## Installation
Tinc virker på mange platforme. Til nogle af dem har vi instruktioner  til installationen.

* [Debian-baserede enheder (Debian / ubuntu / Raspian m.fl)](install-debian.md)
* [Andriod telefoner og tablets](install-android.md)
* Windows
* IOS

## Netværk
Der er flere [adgangspunkter](network.md) til VPN-netværket.
