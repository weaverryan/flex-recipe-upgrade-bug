# Flex Upgrading Bug

* Run `composer update`

Among other things, this will install `symfony/stimulus-bundle`. But because
`symfony/flex` is also upgrading, it will NOT install the `symfony/stimulus-bundle` recipe.

IF you run `composer update` again, it *will* see and install the recipe.
