# filtern

Filters for uBlock Origin [`uBlock Origin`](https://github.com/gorhill/uBlock).

## Naming convention

You can use all of the lists, but keep in mind that lists prefixed with `preferences_` are made for my taste.

To import them into uBlock Origin in one go, the following sections   
can be copied and pasted into the "import url" field of the extension.
Remove the ones you don't need.

```sh
# use programming list
https://codeberg.org/allendema/filtern/raw/branch/main/programming.txt
# use de_DE list
https://codeberg.org/allendema/filtern/raw/branch/main/de.txt
# use sports list
https://codeberg.org/allendema/filtern/raw/branch/main/sports.txt
# use slop_nudges list
https://codeberg.org/allendema/filtern/raw/branch/main/slop_nudges.txt
# use misc list
https://codeberg.org/allendema/filtern/raw/branch/main/misc.txt
# use forums list
https://codeberg.org/allendema/filtern/raw/branch/main/forums.txt
# use social list
https://codeberg.org/allendema/filtern/raw/branch/main/social.txt
# use shopping list
https://codeberg.org/allendema/filtern/raw/branch/main/shopping.txt
# use streaming list
https://codeberg.org/allendema/filtern/raw/branch/main/streaming.txt
# use allowed list
https://codeberg.org/allendema/filtern/raw/branch/main/allowed.txt
```

```sh
# customized
# use preferences_css list
https://codeberg.org/allendema/filtern/raw/branch/main/preferences_css.txt
# use preferences_wiki list
https://codeberg.org/allendema/filtern/raw/branch/main/preferences_wiki.txt
# use preferences_filtering list
https://codeberg.org/allendema/filtern/raw/branch/main/preferences_filtering.txt
# use preferences_hardcore list
https://codeberg.org/allendema/filtern/raw/branch/main/preferences_hardcore.txt
```

## About
List names with the prefix `preferences_` contain some rules which modify appearance, content, cookies, browser local storage, etc. for websites.  
List names with the prefix `preferences_` contain some rules which need to be trusted in uBlock Origin to work.

## trustedListPrefixes
> [!NOTE]
> Depending on which non default settings or filter lists you use, there can be major security and privacy implications.  

Don't use lists with the prefix `preferences_` from my repository as they can change from time to time.  
Therefore it is best to fork and edit such lists and add you own trusted repository to [Advanced Settings](https://github.com/gorhill/uBlock/wiki/Advanced-settings#trustedlistprefixes
) in section [trustedListPrefixes](https://github.com/gorhill/uBlock/wiki/Advanced-settings#trustedlistprefixes).

For example, when using a list which might have previously been good, but now that list got changed to:
  - allow domains you expected to be blocked
  - modify `window.*` properties
  - remove or set cookies
  - modify functions

> [!NOTE]
> Example of [trustedListPrefixes](https://github.com/gorhill/uBlock/wiki/Advanced-settings#trustedlistprefixes) in [Advanced Settings](https://github.com/gorhill/uBlock/wiki/Advanced-settings#trustedlistprefixes)  
> Be sure to point to your trusted repository and not to this repo:  
> ```trustedListPrefixes ublock- https://codeberg.org/allendema/filtern/raw/branch/main/preferences_```

## Issues
Open a new issue if something is not working as you expect.

## Security
[.well-known/security.txt](.well-known/security.txt "Security")  

## License
[GNU General Public License v3.0 or later](./LICENSE "GNU General Public License v3.0 or later")  
SPDX-License-Identifier: GPL-3.0-or-later  
SPDX-FileCopyrightText: © 2019-2026 Allen Dema  
