## INTRODUCTION

The Custom Feeds Migration module is a Module used for migrating Feeds from a URL to Drupal content.

## REQUIREMENTS

Depends on Migrate and Migrate plus module in drupal

## INSTALLATION

Install as you would normally install a contributed Drupal module.
See: https://www.drupal.org/node/895232 for further information.

## Commands
### Command to import and see the status
- `drush cim -y && drush ms`
### Command to stop and reset running migration plugins
- `drush migrate:stop custom_feeds_migration`
- `drush migrate-reset-status custom_feeds_migration`
### Command to import and see the status
- `drush migrate:import custom_feeds_migration`
We can use the limit option to limit the migration to a certain number, e.g : `  --limit=1`
### Command to rollback migration
- `drush migrate-rollback custom_feeds_migration`

## MAINTAINERS

Current maintainers for Drupal 10:

- Razeem Ahmad (razz) - https://www.drupal.org/u/razeem

