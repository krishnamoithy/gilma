<!-- readme -->
<p align="center">
  <a href="https://cometchat.com">
    <img src="./Screenshots/logo.png" alt="CometChat logo" width="180" height="180">
  </a>

  <h2 align="center">Angular Sample Chat App by CometChat</h3>

  <p align="center">
    CometChat Kitchen Sink Sample App (built using <b>CometChat UI Kits</b>) is a fully functional real-time messaging app capable of private (one-on-one), group messaging, voice & video calling.
    <br />
    <a href="https://www.cometchat.com/docs/v4/angular-uikit/overview"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/cometchat-pro/cometchat-chat-sample-app-angular/issues">Report Bug</a>
  </p>
</p>

<div align="center">
    <a href="https://github.com/cometchat-pro/javascript-angular-chat-app/releases" alt="Releases">
        <img src="https://img.shields.io/github/v/release/cometchat-pro/cometchat-pro-angular-sample-app" />
    </a>
    <a href="https://img.shields.io/github/languages/top/cometchat-pro/cometchat-pro-angular-sample-app">
        <img src="https://img.shields.io/github/languages/top/cometchat-pro/cometchat-pro-angular-sample-app" />
    </a>
    <a href="https://github.com/cometchat-pro/cometchat-pro-angular-sample-app/stargazers">
        <img src="https://img.shields.io/github/stars/cometchat-pro/cometchat-pro-angular-sample-app?style=social" />
    </a>
    <a href="https://twitter.com/CometChat">
        <img src="https://img.shields.io/twitter/follow/CometChat?label=CometChat&style=social" />
    </a>
</div>

<!-- TABLE OF CONTENTS -->

## Table of Contents

- [About the Project](#about-the-project)
  - [Built With](#built-with)
- [Getting Started](#getting-started)
  - [Dependencies](#dependencies)
  - [Installing](#installing)
  - [Usage](#usage)
    - [Run locally](#run-project-locally)
  - [Help](#help)
- [Contributing](#contributing)
- [Support](#support)
- [License](#license)
- [About Authors](#about-authors)

<!-- ABOUT THE PROJECT -->

## About The Project

CometChat Kitchen Sink Sample App (built using **CometChat UI Kit**) is a fully functional real-time messaging app capable of private (one-on-one), group messaging, voice & video calling.

### Built With

- [Angular](https://angular.io)
- [CometChat](https://cometchat.com)

<!-- GETTING STARTED -->

## Getting Started

Simply clone or fork this repo and run it using the instructions below to see all features in action. Or use it as a starter template/boilerplate and make edits to suit your needs.

## Dependencies

- CometChat - [Sign up for CometChat](https://app.cometchat.com) and create an app to obtain your keys and other credentials

- npm

  ```sh
  npm install npm@latest -g
  ```

## Installing

1. Clone the repo

   ```sh
   git clone -b v4 https://github.com/cometchat-pro/cometchat-chat-sample-app-angular.git -b v4
   ```

2. Change to the working directory

   ```sh
   cd cometchat-chat-sample-app-angular
   ```

3. Install dependencies via NPM

   ```sh
   npm install
   ```

4. Replace `APP_ID`, `REGION`, and `AUTH_KEY` with your CometChat `App ID`, `Region`, and `Auth Key` in the `src/CONSTS.ts` file.

```sh
export const COMETCHAT_CONSTANTS = {
		APP_ID: "APP_ID",
		REGION: "REGION",
		AUTH_KEY: "AUTH_KEY",
};
```

<!-- USAGE EXAMPLES -->

## Usage

This app contains all features offered by CometChat through its UI Kit. [Read more about the Angular UI Kit here.](https://www.cometchat.com/docs/v4/angular-uikit/overview)

### Run project locally

```sh
ng serve
```
To learn about Angular UI Kit Integration, please click [here](https://www.cometchat.com/docs/v4/angular-uikit/integration).

## Help

To learn more about our UI kits, visit our [documentation](https://www.cometchat.com/docs/v4-uikits).

If you are still facing issues while running this project or integrating with our UI Kits, please connect with our real-time support via the [CometChat Dashboard](https://app.cometchat.com/).

<!-- CONTRIBUTING -->

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**. Sincere thanks to all our [contributors](https://github.com/cometchat-pro/javascript-angular-chat-app/graphs/contributors)!

You are requested to follow the contribution guidelines specified in [CONTRIBUTING.md](./CONTRIBUTING.md) while contributing to the project :smile:.

## Support

Please connect with our real-time support via the [CometChat Dashboard](https://app.cometchat.com/).

<!-- LICENSE -->

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

## About Authors

`cometchat-chat-sample-app-angular` is created & maintained by CometChat.

The names and logos for CometChat are trademarks of CometChat, Inc.

We love open-source software! See [our other projects](https://github.com/cometchat-pro) or [sign up with us](https://app.cometchat.com) to start using our product.
