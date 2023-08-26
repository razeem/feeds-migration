## INTRODUCTION

The Custom Feeds Migration module is a Module used for migrating Feeds from a URL to Drupal content.

## REQUIREMENTS

Depends on Migrate and Migrate plus module in drupal

## INSTALLATION

Install as you would normally install a contributed Drupal module.
See: https://www.drupal.org/node/895232 for further information.

## CONFIGURATION
- Configuration step #1
- Configuration step #2
- Configuration step #3
### Import
  `lando drush cim && lando drush ms`
  `lando drush ms`
  `lando drush migrate:import ndtv_top_posts --limit=1`
  `lando drush migrate-rollback ndtv_top_posts`
  `lando drush migrate:stop ndtv_top_posts`

## MAINTAINERS

Current maintainers for Drupal 10:

- Razeem Ahmad (razz) - https://www.drupal.org/u/razeem

