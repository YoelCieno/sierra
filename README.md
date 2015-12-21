![Sierra cover](http://sierra-library.github.io/img/github/github-cover.png)

Sierra Library
========================================

The smallest and lightest scss library (formerly known as penguin library)

[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/sierra-library/sierra?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

#### Online demo

[Visit demo website](http://sierra-library.github.io/).


What's the difference with other SCSS libraries?
-----------

This is a micro SCSS library to help you build websites in a matter of seconds, without all the arbitrary selectors.

* Only 37.03 kB (8.9 kB gzipped)
* Modular
* 2 grid configurable systems ([bootstrap](http://getbootstrap.com/) and [flexboxgrid](http://flexboxgrid.com/))
* Adjust colors, borders, radius & sizes in the variables.scss file
* Responsive

Installation
-----------

#### 1. Grab a copy of the library

Using bower

```bash
bower install sierra --save
```


Using npm

```bash
npm install sierra-library --save-dev
```

or manually [download the library](https://github.com/sierra-library/sierra/archive/master.zip).

#### 2. Load the css stylesheet in your html file

```html
<link rel="stylesheet" href="dist/sierra.min.css">
```


Customization
-----------
#### 1. Edit variables.scss file
This micro library is ready to be customized by editing the [variables.scss](https://github.com/sierra-library/sierra/blob/master/src/_variables.scss) file.

Start changing:

- Main font: `$basefont`.
- Brand colors: `$brand-primary`,  `$brand-secondary`, `$brand-dark`.
- Buttons border radius: `$button-border-radius`.
- [...]

#### 2. Install dependencies
After editing, run `$ npm install` from the projects root folder to install all dependencies. (needs [nodejs](https://nodejs.org/) installed).

#### 3. Compile the files
Run `$ gulp` to generate a new development file:  `dev/sierra.css`.

or

Run `$ gulp build` to generate a new production file:  `dist/sierra.min.css`.

Tested in production environments
-----------

[![appszoom.com][1]][2] [![appszoom.com/developers][3]][4] [![mobonaut.com][5]][6]

[1]: http://sierra-library.github.io/img/github/logo-appszoom-s.png
[2]: http://www.appszoom.com

[3]: http://sierra-library.github.io/img/github/logo-appszoom-developers-s.png
[4]: http://www.appszoom.com/developers

[5]: http://sierra-library.github.io/img/github/logo-mobonaut-s.png
[6]: http://www.mobonaut.com

Suggesting enhancements and reporting bugs
-----------
Use [GitHub Issues](https://github.com/Sierra-Library/sierra/issues) for suggesting enhancements and reporting bugs.

Contributing rules
-----------

- Open Pull Requests with your changes.
- Do not include many different commits in the same PR.
- Use .editorconfig file located in the root folder.
- Use the .scss-lint file located in the root folder.
- In order to make this library easy to maintain you can use mixins, placeholders and even functions if necessary. The golden rule here is keeping it as simple as possible. Sometimes is better a simple solution that takes a few more lines of code, rather than one that adds complexity for the sake of one-liners. Just use common sense here. In case of doubt join our chat at [sierra-library gitter](https://gitter.im/sierra-library/sierra).
- Many selector names can be improved, but try to avoid changing them (do it only if strictly necessary). We will change them in the V2 with BEM naming.
- If you want to make a big change, suggest it in the [sierra-library gitter](https://gitter.im/sierra-library/sierra) chat. Just to be sure everybody feels confortable with that.

- Happy contributing everyone!

Thanks
-----------
Many thanks to [Angela Lareki](http://larekidesign.squarespace.com/) for collaborating in the design process and [Joan Leon](https://twitter.com/nucliweb) for all the advice on linting files.

License
-----------

This library is licensed under the [GNU General Public License v2.0](https://github.com/sierra-library/sierra/blob/master/LICENSE.md).
