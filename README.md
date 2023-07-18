# Http logger

[![Latest Stable Version](https://img.shields.io/packagist/v/friendsofhyperf/http-logger)](https://packagist.org/packages/friendsofhyperf/http-logger)
[![Total Downloads](https://img.shields.io/packagist/dt/friendsofhyperf/http-logger)](https://packagist.org/packages/friendsofhyperf/http-logger)
[![License](https://img.shields.io/packagist/l/friendsofhyperf/http-logger)](https://github.com/friendsofhyperf/http-logger)

The http logger component for Hyperf.

## Installation

- Request

```bash
composer require "friendsofhyperf/http-logger
```

- Publish

```bash
php bin/hyperf.php vendor:publish friendsofhyperf/http-logger
```

## Usage

```php
return [
    'http' => [
        \FriendsOfHyperf\Http\Logger\Middleware\HttpLogger::class,
    ],
];
```

## Donate

> If you like them, Buy me a cup of coffee.

| Alipay | WeChat | Buy Me A Coffee |
|  ----  |  ----  |  ----  |
| <img src="https://hdj.me/images/alipay-min.jpg" width="200" height="200" />  | <img src="https://hdj.me/images/wechat-pay-min.jpg" width="200" height="200" /> | <img src="https://hdj.me/images/bmc_qr.jpg" width="200" height="200" /> |

<a href="https://www.buymeacoffee.com/huangdijiag" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>

## Contact

- [Twitter](https://twitter.com/huangdijia)
- [Gmail](mailto:huangdijia@gmail.com)

## License

[MIT](LICENSE)
