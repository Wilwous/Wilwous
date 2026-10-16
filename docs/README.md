# Wilwous NET — документация

Официальный справочный раздел проекта. Полные актуальные инструкции находятся на [net.wilwous.ru](https://net.wilwous.ru/?utm_source=community&utm_medium=community&utm_campaign=happ-github-profile-import&utm_content=help).

## Подключение и диагностика

- [Как добавить уже имеющуюся подписку в Happ](https://net.wilwous.ru/guides/happ-subscription?utm_source=community&utm_medium=community&utm_campaign=happ-github-profile-import&utm_content=import): ссылка подписки, буфер обмена и QR.
- [Happ подключён, но нет интернета: что проверить](https://net.wilwous.ru/guides/happ-connected-no-internet?utm_source=community&utm_medium=community&utm_campaign=happ-github-profile-import&utm_content=help): сравнение сетей, состояния подписки, приложений и версий клиента.
- [Happ на Windows: служба или TUN не запускается](https://net.wilwous.ru/guides/happ-windows-service-not-starting?utm_source=community&utm_medium=community&utm_campaign=happ-github-profile-import&utm_content=help): отдельная диагностика запуска локального клиента.

Happ — самостоятельный клиент. Эти материалы Wilwous NET не являются документацией от разработчиков Happ. Источники разработчиков приведены в каждой инструкции.

## iPhone / iPad и российский App Store

На 16 октября 2026 года глобальный Happ доступен в App Store US и Германии; российская версия Happ Lite недоступна. Для российского магазина Wilwous NET уже поддерживает **INCY** (iOS/iPadOS15+). Менять регион Apple ID для NET не требуется.

[Проверенные ссылки установки и возврат к настройке](https://net.wilwous.ru/guides/happ-subscription?utm_source=community&utm_medium=community&utm_campaign=happ-github-profile-import&utm_content=import#ios) находятся в существующей инструкции. После установки откройте свою Personal Access и используйте INCY в быстром подключении либо импорт существующей подписки вручную. Новая покупка для смены клиента не нужна.

## Happ на Mac

- [Happ Desktop снова просит установить VPN helper](happ-macos-helper.md): как отделить запрос прав, уведомление provider, пустой список и сбой службы; без удаления профилей и команд ремонта.

## FAQ по безопасности

**Ссылка Personal Access — это пароль?** Она может предоставлять доступ к управлению вашим аккаунтом. Храните её приватно. Не публикуйте её, QR, UUID или ссылку подписки в GitHub Issues, комментариях и снимках экрана.

**Что показать поддержке?** Модель устройства, версию ОС и клиента, время сбоя, тип сети и точный текст ошибки без секретов. Сначала проверьте журнал и снимок: они могут содержать персональные ссылки.

**Нужно ли отключать проверку сертификатов?** Нет. Не используйте это как способ исправления TLS-ошибки и не импортируйте неизвестные конфигурации из комментариев.

**Можно ли по значку подключения подтвердить работу всех приложений?** Нет. Состояние клиента, загрузка списка подключений и фактическая передача данных — разные проверки.

**Где описана настройка PlayStation / Smart DNS?** Эти инструкции её не подтверждают. Отдельный материал появится только после проверки конкретного сценария.

Дата проверки: 15 октября 2026. Публичные Issues не заменяют личную поддержку и не предназначены для секретов. Исходники production и приватные настройки здесь не публикуются.
