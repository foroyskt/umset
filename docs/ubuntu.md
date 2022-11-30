---
layout: default
title: Ubuntu á Føroyskum
nav_order: 5
permalink: /ubuntu
---

# Ubuntu á Føroyskum

Tað ber nú til, at fáa Ubuntu á føroyskum. Inntil vit hava umsett 5% av stýriskipanini, verður føroyskt ikki útgivið av Ubuntu. Tí hava vit tikið sakina í egnar hendir og lagt okkara egna málpakka út. Hendan vegleiðing vísir á hvussu tú leggur málpakkan inn, og hvussu tú virkir hann.

**GG**: Tað ber einans til at fáa Ubuntu Kinetic á føroyskum.

Tað fyrsta tú skalt gera, er at leggja eitt nýtt pakkasavn inn. Hetta gerst tú við at koyra fylgjandi stýriboð í arbeiðsstøðini:

```bash
sudo add-apt-repository ppa:boginw/faroese
```

Hareftir, skalt tú dagføra tíni pakkasøvn

```bash
sudo apt update
```

Legg síðan málpakkarnir inn við tí fylgnadi:

```bash
sudo apt install language-pack-fo language-pack-fo-base \
    language-pack-gnome-fo language-pack-gnome-fo-base
```

Eftir at hetta er lagt inn, opna so “Settings”, vel “Region & Language”, síðan “Language” og so “Faroese”. Tú verður síðan biðin um at rita út og inn áðrenn mál er virkja.

## Dagføringar

Vit royna at fylgja við nær nýggjir “delta”-pakkar verða útgivnir á [Launchpad](https://translations.launchpad.net/ubuntu/kinetic/+language-packs). Tá ein nýggjur pakki verður útgivin, verða broytingar pakkaðar niður í eina dagføring sum síðan verður útgivin á pakkasavninum. Sum nú er, sær tað út til, at “delta”-pakkarnir verða útgivnir hvønn sunnudag (sí [núverandi skema]), og vit fara at royna at fylgja hesum.

[núverandi skema]: https://dev.launchpad.net/Translations/LanguagePackSchedule
