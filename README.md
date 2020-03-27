## Welcome to Larawal

### Get started

Easy to install like your favourite laravel extension (globally)

```bash
composer require global larawal/installer
```

Move into your favourite destination's path and run

### Create your first blog

```bash
larawal new myblog --from blog
```

### Bricks list

- blog
- ecommerce
- crm
- landing-page

### Adding a brick to a Larawal's project existing

```bash
larawal add myecommerce --from ecommerce
```

### Fetching a brick to a Larawal's project existing

```bash
larawal fetch myecommerce --from ecommerce
```

### Before run

```bash
composer update
```

## Upgrade Larawal

```bash
composer global remove larawal/installer
composer global require larawal/installer --no-cache
```
