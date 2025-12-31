<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Ladder untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/ladder.svg)](https://ci-apps.yunohost.org/ci/apps/ladder/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/ladder.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/ladder.maintain.svg)

[![Pasang Ladder dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=ladder)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Ladder secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Freedom of information is an essential pillar of democracy and informed decision-making. While media organizations have legitimate financial interests, it is crucial to strike a balance between profitability and the public's right to access information. The proliferation of paywalls raises concerns about the erosion of this fundamental freedom, and it is imperative for society to find innovative ways to preserve access to vital information without compromising the sustainability of journalism. In a world where knowledge should be shared and not commodified, paywalls should be critically examined to ensure that they do not undermine the principles of an open and informed society.

Some sites do not expose their content to search engines, which means that the proxy cannot access the content. A future version will try to fetch the content from Google Cache.

Certain sites may display missing images or encounter formatting issues. This can be attributed to the site's reliance on JavaScript or CSS for image and resource loading, which presents a limitation when accessed through this proxy. If you prefer a full experience, please consider buying a subscription for the site.

**Versi terkirim:** 0.0.21~ynh3

## Tangkapan Layar

![Tangkapan Layar pada Ladder](./doc/screenshots/example.png)

## Dokumentasi dan sumber daya

- Depot kode aplikasi hulu: <https://github.com/everywall/ladder>
- Gudang YunoHost: <https://apps.yunohost.org/app/ladder>
- Laporkan bug: <https://github.com/YunoHost-Apps/ladder_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/ladder_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/ladder_ynh/tree/testing --debug
atau
sudo yunohost app upgrade ladder -u https://github.com/YunoHost-Apps/ladder_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
