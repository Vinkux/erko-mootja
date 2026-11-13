# Erko mõõtja

Valgustuse mõõtmise abileht telefonile: näitab mõõtepunkte kaardil koos oma GPS-asukohaga ja laseb luksmeetri
näidud punktidele sisestada.

- Leht: https://vinkux.github.io/erko-mootja/
- Mõõtefaili (`…_mootmine_telefon.json`, vorming `erko-mootmine-1`) teeb Erko Projekteerija; ava see nupuga
  „Ava mõõtefail“. Proovimiseks sobib `naidis_mootmine.json` (väljamõeldud andmed).
- Näidud jäävad telefoni brauserisse (localStorage). Leht ei saada midagi internetti; tulemused
  (`…_mootmine_tulemused_….json` + `.csv`) lähevad välja ainult nupuga „Ekspordi tulemused“.
- Lauaarvutis proovimiseks võltsasukoht: `index.html?asukoht=58.6001,25.0003,3` (lat, lon, täpsus m).

Kood: üks fail `index.html` (HTML + CSS + JS), ilma väliste teekideta.
