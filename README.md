# Drupal Project with predefined PHPUnit configuration

The default Drupal recommended project with configured PHPUnit
and added Drupal Test Helpers module.

## Table of contents

- Installation
- Configuration
- Usage

## Installation

Install as you would normally install a Drupal distribution.
For further information, see [Installing Drupal](https://www.drupal.org/docs/getting-started/installing-drupal).

## Configuration

No additional configuration required.

## Usage

You can run PHPUnit tests for directories defined in PHPUnit configuration
(phpunit.xml) using composer script 'fin composer phpunit'.
Also there is possibility to run this script with path as argument for testing
some separate directory, for example
'fin composer phpunit web/modules/contrib/test_helpers/modules/'.

Also available Coverage report generation for directories defined
in PHPUnit configuration (phpunit.xml) using Docksal command 'fin coverage'.
