# Coming Soon theme

> _Coming Soon_ is a theme for [Cecil](https://cecil.app), powered by [Bootstrap](https://getbootstrap.com).

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
assets:
  compile:
    variables:
      primary: '#69B7FF'
      secondary: '#69C748'
social:
  twitter:
    site: TwitterHandle
```
