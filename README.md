# webservco/symfony-project-skeleton

Application project skeleton using Symfony framework.

## Usage

```shell
git clone git@github.com:webservco/symfony-project-skeleton.git YOUR-PROJECT-NAME
cd YOUR-PROJECT-NAME
git remote rename origin vendor-origin
git remote add origin YOUR-ORIGIN

# Customize (README.md, .ddev/config.yaml)

git branch -M main
git push -u origin main
```

## Development

### Run

```shell
ddev start
ddev composer update
```

### Code validation

Note: if not using doctrine, use `phpstan-symfony.neon` instead of `phpstan-symfony-doctrine.neon`.

```shell
# c is an alias for composer
ddev c check
```

### Symfony

```shell
# alias for ddev exec symfony console
ddev sc PARAMETERS
```

