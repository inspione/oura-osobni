# oura-osobni

Tři statické stránky, které Oura vyžaduje při registraci OAuth aplikace v jejich vývojářském portálu: web, zásady soukromí a podmínky služby.

Nic víc tu není. Vlastní skripty, které data stahují, leží mimo tenhle repozitář a nejsou veřejné, protože obsahují cestu k tokenům.

## Adresy

| Pole ve formuláři Oury | Adresa |
|---|---|
| Website | https://inspione.github.io/oura-osobni/ |
| Privacy Policy | https://inspione.github.io/oura-osobni/privacy.html |
| Terms of Service | https://inspione.github.io/oura-osobni/terms.html |

## Proč to existuje

Oura v prosinci 2025 zrušila osobní přístupové tokeny. Kdo chce od té doby ke svým vlastním datům, musí si zaregistrovat OAuth aplikaci, a ten formulář vyžaduje odkaz na web, zásady soukromí a podmínky, i když jde o jednoho uživatele a jeho vlastní údaje.

Texty na těch stránkách jsou pravdivé: jeden uživatel, data na jednom disku, nic se nesdílí.

## Úpravy

Obyčejné HTML bez závislostí. Změna se projeví na GitHub Pages do minuty po pushi.
