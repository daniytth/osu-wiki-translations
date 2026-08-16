---
tags:
  - announce
  - announce usergroup
  - announce user group
---

# Bejelentési üzenetek

![Bejelentési értesítés](img/notification.png "Egy bejelentési üzenet értesítése")

Egy **bejelentési üzenet** egy speciális üzenettípus, amelynek célja, hogy hosszabb és formázott üzeneteket egyszerre több felhasználónak küldjön el. A hirdetmények és a szokásos csevegőüzenetek közötti legfontosabb különbségek a következők:

- 1024 karakteres korlát a 450 helyett
- Markdown szintaxis támogatása[^note-images] a szöveg formázásához
- Egyszerre több felhasználóhoz történő elküldés
- Lehetőség a „blokkolja a baráti listán nem szereplő személyektől érkező privát üzeneteket” beállítás megkerülésére
- Csak azok a felhasználók válaszolhatnak a bejelentő üzenetekre, akik maguk is küldhetnek ilyen üzeneteket

## Jogosultsági feltételek

A weboldalon keresztül történő bejelentések küldéséhez és megválaszolásához tagság szükséges a [Globális Moderációs Csapatban](/wiki/People/Global_Moderation_Team), a [Jelölésértékelő Csapatban](/wiki/People/Nomination_Assessment_Team) vagy az „announce” [felhasználói csoportban](/wiki/People/User_group). Azonban csak az announce felhasználói csoport tagjai küldhetnek csevegési bejelentéseket az [osu! API v2](https://osu.ppy.sh/docs/index.html#create-channel) segítségével.

### Kérelem benyújtása

Bárki benyújthat csatlakozási kérelmet az „Announce” felhasználói csoporthoz, ha e-mailt küld a [accounts@ppy.sh](mailto:accounts@ppy.sh) címre, a tárgy mezőbe beírva: `Announce Usergroup Request`. Az e-mailt a felhasználó osu!-fiókjához tartozó e-mail-címről kell elküldeni.

Az e-mail szövegében a következőket kell feltüntetni:

- A kérelmező osu! felhasználóneve.
- Egy magyarázat, amelyben röviden ismertetik, miért van szükségük a bejelentési üzenetekre, és milyen gyakorisággal fogják azokat használni.

A [fióktámogatási csapat](/wiki/People/Account_support_team) elbírálja a kérelmet, és értesíti a felhasználót a döntéséről.

## Bejelentési üzenetek küldése

Csevegési bejelentés elküldéséhez nyisd meg a [csevegési oldalt](https://osu.ppy.sh/community/chat), majd kattints a „Bejelentés létrehozása” gombra. Írd be a csatorna nevét, a leírást[^note-desc], a címzettek listáját és az üzenet szövegét. Végül kattints a „Létrehozás” gombra a bejelentés elküldéséhez.

![Bejelentés-létrehozási oldal](img/page.jpg "A bejelentés-létrehozási oldal")

## Érdekességek

- A bejelentési üzenetek célja, hogy közvetlenül helyettesítsék a régi [fórum](/wiki/Community/Forum) üzeneteket.
- A bejelentési rendszer [alapvető megvalósítását](https://github.com/ppy/osu-web/pull/8418) 2022. január 26-án adták hozzá a weboldalhoz. Ez magában foglalta az „announce” felhasználói csoportot és azt a lehetőséget, hogy az API-n keresztül bejelentési üzeneteket lehessen küldeni. A csevegési bejelentések küldésére szolgáló felhasználói felület, valamint a moderátorok számára biztosított küldési lehetőség 2022. június 1-jén [került fel](https://github.com/ppy/osu-web/pull/8747).
- Az „announce” felhasználói csoport azonosítója 47, nincs csoportjelvénye és saját színe sem, a tagok listája pedig privát.

## Jegyzetek

[^note-images]: Képek nem támogattak a bejelentési üzenetekben.
[^note-desc]: Nem úgy mint a többi bevitel mezők, ezeknek a leírása nem kötelező.
