# volto-slate-underline

[![Releases](https://img.shields.io/github/v/release/eea/volto-slate-underline)](https://github.com/eea/volto-slate-underline/releases)

[![Pipeline](https://ci.eionet.europa.eu/buildStatus/icon?job=volto-addons%2Fvolto-slate-underline%2Fmaster&subject=master)](https://ci.eionet.europa.eu/view/Github/job/volto-addons/job/volto-slate-underline/job/master/display/redirect)
[![Lines of Code](https://sonarqube.eea.europa.eu/api/project_badges/measure?project=volto-slate-underline&metric=ncloc)](https://sonarqube.eea.europa.eu/dashboard?id=volto-slate-underline)
[![Coverage](https://sonarqube.eea.europa.eu/api/project_badges/measure?project=volto-slate-underline&metric=coverage)](https://sonarqube.eea.europa.eu/dashboard?id=volto-slate-underline)
[![Bugs](https://sonarqube.eea.europa.eu/api/project_badges/measure?project=volto-slate-underline&metric=bugs)](https://sonarqube.eea.europa.eu/dashboard?id=volto-slate-underline)
[![Duplicated Lines (%)](https://sonarqube.eea.europa.eu/api/project_badges/measure?project=volto-slate-underline&metric=duplicated_lines_density)](https://sonarqube.eea.europa.eu/dashboard?id=volto-slate-underline)

[![Pipeline](https://ci.eionet.europa.eu/buildStatus/icon?job=volto-addons%2Fvolto-slate-underline%2Fdevelop&subject=develop)](https://ci.eionet.europa.eu/view/Github/job/volto-addons/job/volto-slate-underline/job/develop/display/redirect)
[![Lines of Code](https://sonarqube.eea.europa.eu/api/project_badges/measure?project=volto-slate-underline&branch=develop&metric=ncloc)](https://sonarqube.eea.europa.eu/dashboard?id=volto-slate-underline&branch=develop)
[![Coverage](https://sonarqube.eea.europa.eu/api/project_badges/measure?project=volto-slate-underline&branch=develop&metric=coverage)](https://sonarqube.eea.europa.eu/dashboard?id=volto-slate-underline&branch=develop)
[![Bugs](https://sonarqube.eea.europa.eu/api/project_badges/measure?project=volto-slate-underline&branch=develop&metric=bugs)](https://sonarqube.eea.europa.eu/dashboard?id=volto-slate-underline&branch=develop)
[![Duplicated Lines (%)](https://sonarqube.eea.europa.eu/api/project_badges/measure?project=volto-slate-underline&branch=develop&metric=duplicated_lines_density)](https://sonarqube.eea.europa.eu/dashboard?id=volto-slate-underline&branch=develop)


[Volto](https://github.com/plone/volto) add-on

## Features

Demo GIF

## Getting started

### Try volto-slate-underline with Docker

      git clone https://github.com/eea/volto-slate-underline.git
      cd volto-slate-underline
      make
      make start

Go to http://localhost:3000

### Add volto-slate-underline to your Volto project

1. Make sure you have a [Plone backend](https://plone.org/download) up-and-running at http://localhost:8080/Plone

   ```Bash
   docker compose up backend
   ```

1. Start Volto frontend

* If you already have a volto project, just update `package.json`:

   ```JSON
   "addons": [
       "@eeacms/volto-slate-underline"
   ],

   "dependencies": {
       "@eeacms/volto-slate-underline": "*"
   }
   ```

* If not, create one:

   ```
   npm install -g yo @plone/generator-volto
   yo @plone/volto my-volto-project --canary --addon @eeacms/volto-slate-underline
   cd my-volto-project
   ```

1. Install new add-ons and restart Volto:

   ```
   yarn
   yarn start
   ```

1. Go to http://localhost:3000

1. Happy editing!

## Release

See [RELEASE.md](https://github.com/eea/volto-slate-underline/blob/master/RELEASE.md).

## How to contribute

See [DEVELOP.md](https://github.com/eea/volto-slate-underline/blob/master/DEVELOP.md).

## Copyright and license

The Initial Owner of the Original Code is European Environment Agency (EEA).
All Rights Reserved.

See [LICENSE.md](https://github.com/eea/volto-slate-underline/blob/master/LICENSE.md) for details.

## Funding

[European Environment Agency (EU)](http://eea.europa.eu)
