# Major Observatory

## О проекте / токене

Major — проект в Telegram с приложением @major и токеном MAJOR в сети TON. Официальный канал описывает торговлю подарками, аренду NFT-номеров и верификацию каналов через Major Business Card; это самоописание проекта. Контракт MAJOR сверён с реестром Tonkeeper и метаданными TonAPI.

Краткое описание по указанным первичным источникам.

Источники (проверены 2026-11-23):

- <https://t.me/majors>
- <https://t.me/major>
- <https://major.bot/>
- <https://github.com/tonkeeper/ton-assets/blob/main/jettons/MAJOR.yaml>
- <https://tonapi.io/v2/jettons/EQCuPm01HldiduQ55xaBF_1kaW_WAUy5DHey8suqzU_MAJOR>

Generated from https://github.com/Freebielife/TON-Observatory-Template.

Run python3 -m scripts.refresh_observatory; python3 build.py; python3 verify.py.
Publish index.html in TON Sites only after independent on-chain verification.
The initial snapshot is EMPTY: no market data is claimed.
Only native TON swap pairs supported. Locks, staking and custom project NFT badges are configured through project.json and verified against TonAPI.
Configure your GitHub workflow scheduler before launch.

Foundation version: 1.3.0. Holders show 10, expandable to top 20.
`project.json` is the per-project specification. Contract/pool/precision changes require regenerating from the factory; do not reuse another token's snapshot.
Run `python3 build.py` for an atomic bundle and `build/report.json` size report.
No external fonts, scripts or images are needed to render the saved page. Fresh data checks and manual wallet lookups require network access.
Cloudflare dispatch registration and GitHub repository access remain separate deployment steps. No credentials go into HTML.

## Создание Major

Основа: TON-Observatory-Template 1.3.0, commit c618b19f51fcfa44264e753a6945419d63934992.
Флаг разделов: анимированный TONecoFlags №003, выбран пользователем.
Логотип: https://major.bot/favicon.png — резервный официальный источник; SVG из метаданных возвращал HTTP 404.
Нативный GitHub cron :10/:40 UTC служит резервом; плановые запуски требуют отдельной проверки.
TON Storage / RT пока не опубликован.
