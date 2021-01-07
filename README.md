# Information / Информация

Пакет русской локализации **Flarum EXTended**.

## Install / Установка

**Flarum** использует [**Composer**](https://getcomposer.org/) для управления зависимостями и расширениями.

Русский пакет локализации доступен в [**Packagist**](https://packagist.org/packages/marketplace/flarum-l10n-ext-russian) и может быть установлен при помощи **Composer**.

Убедитесь, что **Composer** установлен на вашем компьютере, и введите следующую команду в терминале, находясь в корневой директории **Flarum**:

```
composer require marketplace/flarum-l10n-ext-russian
```

Так же, данная команда может быть использована для обновления языкового пакета, без обновления сторонних компонентов.

Обратите внимание, что пакет локализации будет добавлен в качестве зависимости **Flarum**, и он также будет автоматически обновляться при обновлении движка форума.

## Update / Обновление

Для обновления локализации необходимо выполнить следующие команды:

```
composer update marketplace/flarum-l10n-ext-russian
php flarum cache:clear
```

## Donations

- [Donation Form](https://donation-form.github.io/)
