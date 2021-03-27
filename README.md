# tinc.cloud
AlsLUG's VPN-netværk

## Generelt
tinc.cloud er basseret på [tinc](https://www.tinc-vpn.org/) som er et open-source distriburert VPN-netværk.

Fordelen ved at bruge tinc i stedet for fx OpenVPN er at vi ikke er afhængige af en central server. Hverken til authentication eller til at route trafikken.

- hvis du har adgang til bare en enkelt af de offentlige servere, har du som udgangspunkt adgang til alle services.
- alle kan som udgangspunkt kommunikere med alle. Med et lille trick kan adgangen til en enhed begrænses til kun at tillade bestemte enheder.
- kommunikationen i netværket kører peer-to-peer, så trafikken mellem fx din telefon og din nextcloud-server hjemme i kosteskabet kører ikke gennem central servere.

## Installation

### Debian-baserede enheder (Debian / ubuntu / Raspian m.fl)

~~~
curl -s https://keys.tinc.cloud/get.sh | bash
~~~

### Andriod

[The tinc Android application](https://tincapp.pacien.org/)

App'en skal konfigureres manuelt. 

### Windows

### IOS

## Netværk

### AlsLUGs servere

- Hetzner, Nürnberg, Bayern, Tyskland
- Hetzner, Falkenstein/Vogtland, Sachsen, Tyskland

### Wangerins servere

- Linode, London, England
- Hetzner, Helsinki, Finland
- Yourserver.se, Falkenberg, Sverige
