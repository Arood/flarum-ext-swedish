# flarum-ext-swedish
The Swedish language extension for [Flarum](http://flarum.org/).

## Information
**Stable:** [1.0.0](https://github.com/nlssn/flarum-ext-swedish/archive/v1.0.0.zip) | **Unstable:** [1.0.0-dev](https://github.com/nlssn/flarum-ext-swedish/archive/master.zip) | **Requires:** Flarum v0.1.0-beta.6

This project aims to be a central repo for Swedish translations of the Flarum forum software and many popular community made extensions.

**Want to help out?**
- Report [issues here on GitHub](https://github.com/nlssn/flarum-ext-swedish/issues) or in the [Flarum Community thread](https://discuss.flarum.org/d/5615-swedish-language-extension).
- Give [suggestions](https://github.com/nlssn/flarum-ext-swedish/issues) on which [community extensions](https://discuss.flarum.org/t/extensions) should be translated next.
- Clone the [English Language Pack](https://github.com/flarum/flarum-ext-english) and translate it to your own language. Be sure to check for [existing](https://github.com/moutonnoireu/flarumextlist/wiki/Extension-List) [translations](https://discuss.flarum.org/t/languages) first.
- Star this repo on GitHub.
- Send me a [nice tweet](http://twitter.com/iamnlssn) ;)

## Installation
To install this extension start by running the following command in your Flarum root folder:
```
composer require nlssn/flarum-ext-swedish
```
Then activate the extension under _Admin Panel > Extensions_ section.<br>
Lastly you can go to to the _Basics_ section and set the _Default Language_.

If you want to try the unstable version you can run `composer require nlssn/flarum-ext-swedish dev-master` instead.<br>
If you ever need to update, just run `composer update` in your Flarum root folder.

## Extension Compatibility
This project mainly translates the Flarum Core and it's bundled extensions, but it's also compatible with the following community created extensions:
- [**filter**](https://github.com/issyrocks12/flarum-ext-filter) by issyrocks12 _(v1.2.1)_
- [**gamification**](https://gitlab.com/ReFlar/gamification) by ReFlar _(v0.1.0-beta.6.2)_
- [**links**](https://github.com/sijad/flarum-ext-links) by sijad _(v0.1.0-beta.6)_
- [**money**](https://github.com/AntoineFr/flarum-ext-money) by AntoineFr _(v0.4.0)_
- [**recaptcha**](https://github.com/sijad/flarum-ext-recaptcha) by sijad _(v0.0.2)_
- [**twofactor**](https://github.com/issyrocks12/flarum-ext-twofactor) by issyrocks12 _(v1.0.0)_

## Thanks
A big thanks to [@acarlsson](https://github.com/acarlsson) who created [the first Swedish language extension](https://github.com/acarlsson/flarum-ext-swedish) for Flarum. A lot of the initial translations came from that project. Some things were changed, more has been (and will continue to be) added. Again, thank you!

## License
Released under the MIT License. Please see the [LICENSE](https://github.com/nlssn/flarum-ext-swedish/blob/master/LICENSE) file.
