### GreenBit

🌿 A green, pure and nice [Hexo](https://www.hexo.io) theme for a personal blog, base on [apollo](https://github.com/pinggod/hexo-theme-apollo) and [geist-ui](https://github.com/geist-org/geist-ui).

🌱 [demo](https://www.rayliao.com/hexo-theme-greenbit/)

### Install

```bash
hexo init blog
cd blog
npm install
git clone https://github.com/rayliao/hexo-theme-greenbit.git themes/greenbit
```

### Start

Modify the `theme` configuration item of `_config.yml` to `greenbit`:

```yaml
theme: greenbit

# Show all articles on archive page
# Requires hexo-generator-archive plugin support installed above
archive_generator:
  per_page: 0
  yearly: false
  monthly: false
  daily: false
```

### Update

```bash
cd themes/greenbit
git pull
```

### License

MIT
