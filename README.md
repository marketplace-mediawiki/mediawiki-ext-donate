# Information / Информация

Система пожертвований на:

- Yandex.Money;
- банковскую карту;
- счёт PayPal;
- кошелёк Bitcoin;
- кошелёк Ethereum;
- кошелёк Monero.

## Install / Установка

1. Загрузите папки и файлы в директорию `extensions/MW_EXT_Donate`.
2. В самый низ файла `LocalSettings.php` добавьте строку:

```php
wfLoadExtension( 'MW_EXT_Donate' );
```

## Syntax / Синтаксис

```html
{{#donate: ya-wallet =
  |card =
  |paypal =
  |bitcoin =
  |monero =
  |ethereum =
}}
```

## Donations / Пожертвования

- [Donation Form](https://donation-form.github.io/)
