# Crypto

> IMPORTANT: this fork's entire purpose is to enable compatibility with Laravel 8.x and beyond.  
> **OUTSIDE OF ENSURING COMPATIBILITY, NO FEATURE ADDITIONS/CHANGES OR BUG FIXES WILL BE MADE!**

**Crypto** - Powerful and elegant cryptography tools for Laravel and Lumen

[![license](https://img.shields.io/github/license/mashape/apistatus.svg)](https://packagist.org/packages/squatto/grafite-crypto)

The Cryptograpy toolset Crypto provides a collection of methods for handy, encryption, decryption, uuid generating, app key generating and more.

##### Author(s):
* [Matt Lantz](https://github.com/mlantz) ([@mattylantz](http://twitter.com/mattylantz), mattlantz at gmail dot com) - original [grafite/crypto package](https://packagist.org/packages/grafite/crypto) author
* [Scott Carpenter](https://github.com/squatto) - current package author

## Requirements

1. PHP 7.3+
2. OpenSSL
3. Laravel 8.0+ or Lumen

* For Lumen you must enable Facades: `$app->withFacades()`

## Compatibility and Support

| Laravel Version | Package Tag | Supported |
|-----------------|-------------|-----------|
| 8.x | 1.3.x | no |
| 7.x | 1.2.x | no |

----

### Installation

Start a new Laravel project:
```shell script
composer create-project laravel/laravel your-project-name
```

Then run the following to add Crypto:
```shell script
composer require squatto/grafite-crypto
```

## Documentation

[https://docs.grafite.ca/others/crypto](https://docs.grafite.ca/others/crypto)

## License
Crypto is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT)

### Bug Reporting and Feature Requests
Please add as many details as possible regarding submission of issues and feature requests

### Disclaimer
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
