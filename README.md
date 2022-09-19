A green, pure and nice [hexo](https://www.hexo.io) theme for a personal blog, base on [apollo](https://github.com/pinggod/hexo-theme-apollo) and [geist-ui](https://github.com/geist-org/geist-ui), inspired by [cactus](https://github.com/probberechts/hexo-theme-cactus) and [douban](https://www.douban.com/)

🌱 [Demo](https://rayliao.github.io/hexo-theme-greenbit/)

> [Green Bit](https://onepiece.fandom.com/wiki/Green_Bit) is a seemingly uninhabited island in the New World located immediately north of Dressrosa. Law first mentioned the island when he was speaking to Smoker on Punk Hazard. Its underground is home to the Tontatta Kingdom.

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
