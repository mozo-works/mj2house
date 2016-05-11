# mj2house

박미정 작가의 포트폴리오 웹사이트. 드루팔 컴포저 프로젝트로 제작.

- [install composer](https://getcomposer.org/doc/00-intro.md#installation-linux-unix-osx)
- [Composer template for Drupal projects](https://github.com/drupal-composer/drupal-project/tree/7.x)

## development

```
$ cp .env.yml.example .env.yml
$ vi .env.yml # add database dsn and other configs.
$ composer install
$ cd docroot && ../vendor/bin/drush rs /
```
