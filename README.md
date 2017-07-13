# ![logo](/examples/assets/instagram.png) Instagram PHP [![Latest Stable Version](https://poser.pugx.org/mgp25/instagram-php/v/stable)](https://packagist.org/packages/mgp25/instagram-php) [![Total Downloads](https://poser.pugx.org/mgp25/instagram-php/downloads)](https://packagist.org/packages/mgp25/instagram-php) ![compatible](https://img.shields.io/badge/PHP%207-Compatible-brightgreen.svg) [![License](https://poser.pugx.org/mgp25/instagram-php/license)](https://packagist.org/packages/mgp25/instagram-php)

This is Instagram's private API. It has almost all the features the Instagram app has, including media upload, direct messaging, stories and more.

**Read the [wiki](https://github.com/mgp25/Instagram-API/wiki)** and previous issues before opening a new one! Maybe your issue has already been answered.

**Frequently Asked Questions:** [F.A.Q.](https://github.com/mgp25/Instagram-API/wiki/FAQ)

**Do you like this project? Support it by donating**

**mgp25**

- ![Paypal](https://raw.githubusercontent.com/reek/anti-adblock-killer/gh-pages/images/paypal.png) Paypal: [Donate](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=5ATYY8H9MC96E)
- ![btc](https://raw.githubusercontent.com/reek/anti-adblock-killer/gh-pages/images/bitcoin.png) Bitcoin: 1DCEpC9wYXeUGXS58qSsqKzyy7HLTTXNYe

**stevejobzniak**

- ![Paypal](https://raw.githubusercontent.com/reek/anti-adblock-killer/gh-pages/images/paypal.png) Paypal: [Donate](https://www.paypal.me/Armindale/0usd)
- ![btc](https://raw.githubusercontent.com/reek/anti-adblock-killer/gh-pages/images/bitcoin.png) Bitcoin: 18XF1EmrkpYi4fqkR2XcHkcJxuTMYG4bcv

----------
## Installation

### Using Composer

```sh
composer require mgp25/instagram-php
```

```php
require __DIR__.'/../vendor/autoload.php';

$ig = new \InstagramAPI\Instagram();
```

If you want to test new and possibly unstable code that is in the master branch, and which hasn't yet been released, then you can use master instead (at your own risk):

```sh
composer require mgp25/instagram-php dev-master
```


### I don't have Composer

You can download it [here](https://getcomposer.org/download/).

## Examples

All examples can be found [here](https://github.com/mgp25/Instagram-API/tree/master/examples).

## Code of Conduct

This project adheres to the Contributor Covenant [code of conduct](CODE_OF_CONDUCT.md).
By participating, you are expected to uphold this code.
Please report any unacceptable behavior.

## How do I contribute

If you would like to contribute to this project, please feel free to submit a pull request.

Before you do, take a look at the [contributing guide](https://github.com/mgp25/Instagram-API/blob/master/CONTRIBUTING.md).

## Why did I make this API?

After legal measures, Facebook, WhatsApp and Instagram blocked my accounts.
In order to use Instagram on my phone I needed a new phone, as they banned my UDID, so that is basically why I made this API.

### What is Instagram?
According to [the company](https://instagram.com/about/faq/):

> "Instagram is a fun and quirky way to share your life with friends through a series of pictures. Snap a photo with your mobile phone, then choose a filter to transform the image into a memory to keep around forever. We're building Instagram to allow you to experience moments in your friends' lives through pictures as they happen. We imagine a world more connected through photos."

# License

In order help ensure fairness and sharing, this library is dual-licensed. Be
aware that _all_ usage, unless otherwise specified, is under the **RPL-1.5**
license!

- Reciprocal Public License 1.5 (RPL-1.5): https://opensource.org/licenses/RPL-1.5

You should read the _entire_ license; especially the `PREAMBLE` at the beginning.
In short, the license _requires_ that you open-source _all_ of your own source
code for _any_ project which uses this library!

Furthermore, the library is _also_ available _to certain entities_ under a
modified version of the RPL-1.5, which has been modified to allow you to use the
library _without_ open-sourcing your own project. The modified license
(see [LICENSE_PREMIUM](https://github.com/mgp25/Instagram-API/blob/master/LICENSE_PREMIUM))
is granted to certain entities, at _our_ discretion, and for a _limited_ period
of time (unless otherwise agreed), pursuant to our terms. Currently, we are
granting this license to all
"[premium subscribers](https://github.com/mgp25/Instagram-API/issues/1231)" for
the duration of their subscriptions. You can become a premium subscriber by
either contributing substantial amounts of high-quality code, or by subscribing
for a fee. This licensing ensures fairness and stimulates the continued growth
of this library through both code contributions and the financial support it
needs.

You are not required to accept this License since you have not signed it,
however _nothing else_ grants you permission to _use_, copy, distribute, modify,
or create derivatives of either the Software (this library) or any Extensions
created by a Contributor. These actions are prohibited by law if you do not
accept this License. Therefore, by performing any of these actions You indicate
Your acceptance of this License and Your agreement to be bound by all its terms
and conditions. IF YOU DO NOT AGREE WITH ALL THE TERMS AND CONDITIONS OF THIS
LICENSE DO NOT USE, MODIFY, CREATE DERIVATIVES, OR DISTRIBUTE THE SOFTWARE. IF
IT IS IMPOSSIBLE FOR YOU TO COMPLY WITH ALL THE TERMS AND CONDITIONS OF THIS
LICENSE THEN YOU CAN NOT USE, MODIFY, CREATE DERIVATIVES, OR DISTRIBUTE THE
SOFTWARE.

# Terms and conditions

- You will NOT use this API for marketing purposes (spam, botting, harassment, massive bulk messaging...).
- We do NOT give support to anyone who wants to use this API to send spam or commit other crimes.
- We reserve the right to block any user of this repository that does not meet these conditions.

## Legal

This code is in no way affiliated with, authorized, maintained, sponsored or endorsed by Instagram or any of its affiliates or subsidiaries. This is an independent and unofficial API. Use at your own risk.
