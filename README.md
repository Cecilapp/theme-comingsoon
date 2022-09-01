# Coming Soon theme

_Coming Soon_ is a theme for [Cecil](https://cecil.app), powered by [Start Bootstrap Coming Soon](https://github.com/StartBootstrap/startbootstrap-coming-soon) and [Bootstrap](https://getbootstrap.com), with [Netlify Forms](https://www.netlify.com/products/forms/) integration.

[![Coming Soon preview](/docs/screenshot.png)](https://cecilapp.github.io/theme-comingsoon/)

## Installation

```bash
composer require cecil/theme-comingsoon
```

> Or [download the latest archive](https://github.com/Cecilapp/theme-comingsoon/releases/latest/) and uncompress its content in `themes/comingsoon`.

### Install Bootstrap

Run the following command:

```bash
cd themes/comingsoon/static && npm install
```

## Usage

### Configure Cecil

Add `comingsoon` in the `theme` section of your `config.yml`:

```yaml
theme:
  - comingsoon
```

**Example:**

```yaml
theme:
  - comingsoon
comingsoon:
  # customize subscribe form
  subscribe:
    placeholder: Enter Email...
    button: Notify me!
assets:
  compile:
    # customize colors
    variables:
      primary: '#69B7FF'
      secondary: '#69C748'
social:
  twitter:
    site: TwitterHandle
  github:
    username: Username
```

## License

_Coming Soon_ is a free software distributed under the terms of the MIT license.

© [Arnaud Ligny](https://arnaudligny.fr)
