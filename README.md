Phing Drupal Tests
=============

## Overview

A collection of automated Drupal testing targets for Phing.

## Installation

This project can be checked out with Composer.

```
"require": {
    "doghouseagency/phing-drupal-tests": "*"
}
```

If you are already running a Phing build in an existing project why not
include these tasks as well with the following line in your build.xml:

```
<import file="vendor/doghouseagency/phing-drupal-tests/build.xml" optional="true" />
```

## Usage

To run the default set of tests.

```
phing tests
```
