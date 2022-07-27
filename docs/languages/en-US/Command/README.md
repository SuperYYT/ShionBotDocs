# Command

## Inquire the Wiki
1. `Wiki name:What to search`

Example:
```
mw:home
```

2. `[[What to search]]`

Example:
```
[[home]]
```

## /help
1. `/help`

**Help**

Example:
```
/help
```

## /userinfo
1. `/userinfo`

**Search for your own user information**

Example:
```
/userinfo
```

## /language
::: warning Notice
The modification takes effect only for the user who runs the command and has a higher priority than the default configuration. If you need to modify the default configuration, modify the [configuration file](How-to-ues/configyml-template.md)
:::

1. `/language`

**Displays a list of available languages**

Example:
```
/language
```

2. `/language language`

**Change language**

Example:
```
/language zh-CN
```

## /wikiadd
::: warning Warning
The modification takes effect only for the user who runs the command and has a higher priority than the default configuration. If you need to modify the default configuration, modify the [configuration file](How-to-ues/configyml-template.md)
:::
::: tip About custom Wiki systems
Only `HTTP` sites can be added, and the target Wiki must be accessible to the robot's server

If MediaWiki is deployed in a non-root directory, then The `Wiki link` also need to fill in the corresponding path. For example, the wikipedia API address is `https://zh.wikipedia.org/w/api.php`, you need to fill out `zh.wikipedia.org/w`
:::

1. `/wikiadd <Wiki Name> <Wiki Link>`

**Add a MediaWiki site**

Example:
```
/wikiadd mg zh.moegirl.org.cn
```

## /wikiupdate
::: warning Warning
The modification takes effect only for the user who runs the command and has a higher priority than the default configuration. If you need to modify the default configuration, modify the [configuration file](How-to-ues/configyml-template.md)
:::

1. `/wikiupdate <Wiki Name> <Wiki Link>`

**Update the link to the MediaWiki site that you have added**

Example:
```
/wikiupdate mg zh.moegirl.org.cn
```

## /wikidelete
::: warning Warning
The modification takes effect only for the user who runs the command and has a higher priority than the default configuration. If you need to modify the default configuration, modify the [configuration file](How-to-ues/configyml-template.md)
:::

1. `/wikidelete <Wiki Name>`

**Delete a MediaWiki site that has been added**

Example:
```
/wikidelete mg
```

## /importdata
::: warning Notice
The modification takes effect only for the user who runs the command and has a higher priority than the default configuration. If you need to modify the default configuration, modify the [configuration file](How-to-ues/configyml-template.md)
:::

1. `/importdata <Software name> <User ID>`

**Cross-platform import configuration data of other users, such as languages and Wiki sites**

Example:
```
/importdata Telegram 1000000000
```
