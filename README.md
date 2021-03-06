# React Starter

A basic template that consists of the essential elements that are required to start building a React application.

The template consists of:

* a typcial project layout structure
* babel setup and configuration
* webpack setup and configuration
* eslint setup and configuration
* SCSS setup and configuration
* the main React components to get started

Additionaly, the template provides a development and production webpack configuration.

The template also allows one to include specific plugins as part of build. [Please see here for more detail](#build-application-with-bundleanalayzer-plugin-included)

---

## Developed With

* [Node.js](https://nodejs.org/en/) - Javascript runtime
* [React](https://reactjs.org/) - A javascript library for building user interfaces
* [Babel](https://babeljs.io/) - A transpiler for javascript
* [Webpack](https://webpack.js.org/) - A module bundler
* [SCSS](http://sass-lang.com/) - A css metalanguage

---

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

The following software is required to be installed on your system:

* Node 8.x
* Npm 3.x

Type the following commands in the terminal to verify your node and npm versions

```bash
node -v
npm -v
```

### Install

Follow the following steps to get development environment running.

* Clone _'react-starter'_ repository from GitHub

  ```bash
  git clone https://github.com/drminnaar/react-starter.git
  ```

  _OR USING SSH_

  ```bash
  git clone git@github.com:drminnaar/react-starter.git
  ```

* Install node modules

  ```bash
  cd react-starter
  npm install
  ```

### Build

#### Build Application

|        dev        |        prod        |
| :---------------: | :----------------: |
| npm run build:dev | npm run build:prod |

#### Build Application And Watch For Changes

|           dev           |           prod           |
| :---------------------: | :----------------------: |
| npm run build:dev:watch | npm run build:prod:watch |

#### Build Application With BundleAnalayzer Plugin Included

|               dev               |               prod               |
| :-----------------------------: | :------------------------------: |
| npm run build:dev:bundleanalyze | npm run build:prod:bundleanalyze |

After running the above command, a browser window will open displaying an interactive graph resembling the following image:

![bundle-analyzer](https://user-images.githubusercontent.com/33935506/36382812-eadf199e-1592-11e8-9681-cf5ccf67951f.png)

#### Build Application With BundleBuddy Plugin Included

|              dev              |              prod              |
| :---------------------------: | :----------------------------: |
| npm run build:dev:bundlebuddy | npm run build:prod:bundlebuddy |

### Run ESlint

#### Lint Project Using ESLint

```bash
npm run lint
```

#### Lint Project Using ESLint, and autofix

```bash
npm run lint:fix
```

### Run

#### Run Start

This will run the _'serve:dev'_ npm task

```bash
npm start
```

#### Run Dev Server

```bash
npm run serve:dev
```

#### Run Dev Server With Dashboard

```bash
npm run serve:dev:dashboard
```

The above command will display a dashboard view in your console resembling the following image:

![webpack-dashboard](https://user-images.githubusercontent.com/33935506/36382813-eb10b0a8-1592-11e8-9506-fd25db65a258.png)

#### Run Prod Server

This command will build application using production settings and start the application using _live-server_

```bash
npm run serve:prod
```

---

## Versioning

I use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/drminnaar/react-starter/tags).

---

## Authors

* **Douglas Minnaar** - _Initial work_ - [drminnaar](https://github.com/drminnaar)

[react-starter]: https://github.com/drminnaar/react-starter
[react-redux-starter]: https://github.com/drminnaar/react-redux-starter
[react-clicker]: https://github.com/drminnaar/react-clicker
[react-clock-basic]: https://github.com/drminnaar/react-clock-basic
[react-timer-basic]: https://github.com/drminnaar/react-timer-basic
[react-timer-advanced]: https://github.com/drminnaar/react-timer-advanced
[react-masterminds]: https://github.com/drminnaar/react-masterminds
[react-movie-cards]: https://github.com/drminnaar/react-movie-cards
[react-calculator-standard]: https://github.com/drminnaar/react-calculator-standard
[react-bitcoin-monitor]: https://github.com/drminnaar/react-bitcoin-monitor
[react-weather-standard]: https://github.com/drminnaar/react-weather-standard
[react-redux-quotlify]: https://github.com/drminnaar/react-redux-quotlify
