![Code Coverage](https://img.shields.io/endpoint?url=https://gist.githubusercontent.com/frank-bee/819f17e6f8166534e73c8acf9ee58726/raw/api-commons-lib.json)
# YAKU Commons Libs
This repository is the central place for all backend libraries and currently contains the API commons lib. It is a monorepo using [turborepo](https://turbo.build/repo/docs).

## Turborepo

This repo is a monorepo using turborepo with [npm](https://www.npmjs.com/) as a package manager. A short introduction to turborepo can be found [here](https://turbo.build/repo/docs).


### Build

To build all libraries, run the following command:

```
npm run build
```

### Lint

To lint all libraries, run the following command:

```
npm run lint
```

### Format

To format all apps and packages, run the following command:

```
npm run format
```

## Workflows

Workflows for this repository:

TBD

## Included libraries

### YAKU API Common Lib

The folder`./libs/api-commons-lib` contains the API Commons library.

The library contains:

* **Input Validator**: Utility to validate request inputs
* **Query-Param-Handling Service**: Generic way to handle query params, especially pagination-related, in Nest Controllers
* **URL-Handler**: Utility to manipulate URLs

### YAKU API KeyCloak Auth Lib

The folder`./libs/api-keycloak-auth-lib` contains the API KeyCloak Auth library.

The library contains:

* **KeyCloak Module**: A Nest module that can be easily imported into Nest projects.
* **KeyCloak Service**: A service that introspects the token from requests to determine its validity and current state.
* **KeyCloak Strategy**: A strategy that can be used as a guard to validate the tokens coming from requests.

#### Installation

TBD

To install the library in another project, run the following command:

```
npm install --save @B-S-F/api-commons-lib
```