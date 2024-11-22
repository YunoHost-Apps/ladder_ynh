<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Ladder YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/ladder.svg)](https://ci-apps.yunohost.org/ci/apps/ladder/) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/ladder.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/ladder.maintain.svg)

[![Instalatu Ladder YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=ladder)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Ladder YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Freedom of information is an essential pillar of democracy and informed decision-making. While media organizations have legitimate financial interests, it is crucial to strike a balance between profitability and the public's right to access information. The proliferation of paywalls raises concerns about the erosion of this fundamental freedom, and it is imperative for society to find innovative ways to preserve access to vital information without compromising the sustainability of journalism. In a world where knowledge should be shared and not commodified, paywalls should be critically examined to ensure that they do not undermine the principles of an open and informed society.

Some sites do not expose their content to search engines, which means that the proxy cannot access the content. A future version will try to fetch the content from Google Cache.

Certain sites may display missing images or encounter formatting issues. This can be attributed to the site's reliance on JavaScript or CSS for image and resource loading, which presents a limitation when accessed through this proxy. If you prefer a full experience, please consider buying a subscription for the site.

**Paketatutako bertsioa:** 0.0.21~ynh3

## Pantaila-argazkiak

![Ladder(r)en pantaila-argazkia](./doc/screenshots/example.png)

## Dokumentazioa eta baliabideak

- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/everywall/ladder>
- YunoHost Denda: <https://apps.yunohost.org/app/ladder>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/ladder_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/ladder_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/ladder_ynh/tree/testing --debug
edo
sudo yunohost app upgrade ladder -u https://github.com/YunoHost-Apps/ladder_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
