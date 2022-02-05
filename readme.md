# Renovate classifier handling issue reproducer

This is a reproducer for https://github.com/renovatebot/renovate/issues/5619.

It is expected that the version for `org.immutables:value` is updated in all 3 referenced locations, but it is only updated for the two without a classifier specified.

See the renovate-produced pull request for details.