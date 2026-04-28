# diabetiki.asia

## Статус
На ревью у клиента. После приёмки — перенести домен на акк клиента.

## Хостинг
GitHub Pages — мой аккаунт (mnurganat)
Домен: diabetiki.asia — ps.kz, мой аккаунт

## Деплой
git add . && git commit -m "fix" && git push
GitHub Pages автодеплой ~1 мин

## Стек
HTML / CSS / JS
Один файл: index.html

## Частые задачи
- Цены: искать в index.html по слову "цена" / "тенге" / "₸"
- GTag / GA4: вставить перед </head>
- Контент: всё в index.html

## SEO статус
Сделано:
- GA4 (G-ZZFKFF73LN)
- meta description / keywords / viewport / canonical
- Schema.org Organization (минимум: name, url, description)
- robots.txt
- sitemap.xml

TODO (ждём данные от клиента):
- favicon (ждём от клиента)
- Schema.org: телефон, email, адрес, соцсети, logo URL
  → если есть физ. точка — поменять @type на LocalBusiness + добавить address/openingHours
- OG / Twitter теги (для превью в WhatsApp/TG/FB) — нужен OG-image 1200×630
- Yandex.Metrika ID (важно для KZ-рынка / Я.Директ)
- Meta Pixel (если будет реклама в Instagram/FB)
- Поданные карты:
  - Google Search Console — подтвердить домен, отправить sitemap
  - Яндекс.Вебмастер — подтвердить, отправить sitemap
- robots.txt и sitemap.xml — после деплоя проверить:
  https://diabetiki.asia/robots.txt
  https://diabetiki.asia/sitemap.xml
