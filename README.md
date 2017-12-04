# pysjs-mock-site

[![build](https://travis-ci.org/neetjn/pysjs-mock-site.svg?branch=master)](https://travis-ci.org/neetjn/pysjs-mock-site)
[![Join the chat at https://gitter.im/riot-view-router/Lobby](https://badges.gitter.im/riot-view-router/Lobby.svg)](https://gitter.im/riot-view-router/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Mock website created with angular.js 1.6 and bulmacss for unit testing [pyselenium-js](git@github.com:neetjn/pyselenium-js.git).

### Use

Bundles can be built like so,

```bash
npm run build
``` 

To serve the website,

```bash
npm run app
```

You may alternatively run the website in the background,

```
npm run app:detached
```

### Contributors

* **John Nolette** (john@neetgroup.net)

Contributing guidelines are as follows,

* When adding new features to the mock website, make sure it doesn't effect any existing pyselenium-js unit tests.
* Branches for bugs and features should be structued like so, `issue-x-username`.
* Include your name and email in the contributors list.

---
Copyright (c) 2017 John Nolette Licensed under the MIT license.
