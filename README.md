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
Initial on-chain snapshot collected; individual freshness and history coverage are recorded in data/snapshot.json.
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

## Покрытие операций

Лента собирает подтверждённые прямые обмены MAJOR/TON на STON.fi v2 и DeDust.
Основной график использует STON.fi v2 (проверенная ликвидность выше DeDust); цены разных пулов не смешиваются.
Другие пары отображаются в разделе пулов, но не включаются в заявленное покрытие ленты.
История достраивается постепенно; неполные периоды отмечаются.
Исправление распознавания GeckoTerminal stonfi-v2 сохранено в общей основе: 65780137fa12eda7500f48d29c5b261411305274.
Общий планировщик: 30 минут, фаза :10/:40 UTC; регистрация в исходниках добавлена, реальный плановый запуск требует подтверждения.
