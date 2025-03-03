
# Snackify

Snackify is a Node.js module designed to simplify the process of transferring a local Expo project to an Expo Snack. It allows developers to quickly create an Expo Snack from the current state of their local Expo project, making it easier to share and demo their React Native applications.

Note: The [Expo](https://expo.dev) name and logo are trademarks of 650 Industries, Inc. This project is built and maintained by [danstepanov](https://github.com/danstepanov) and not by the Expo team.

## Features

- Easy creation of Expo Snacks from local Expo projects.
- Automated handling of file transfers to Expo Snack.
- Quick sharing of React Native projects for collaboration and demonstration.

## Installation

To install Snackify, run the following command in your terminal:

```bash
npm install -g create-snack
```

This will install Snackify globally on your machine, allowing you to use it in any Expo project.

## Usage

Navigate to the root directory of your Expo project and run:

```bash
npx create snack
```

The command scans all the files in your Expo project, excluding `node_modules` and `.git`, and creates a new Expo Snack. Upon completion, it provides a URL to the created Expo Snack.

## Requirements

- Node.js installed on your system.
- An existing Expo project to convert into a Snack.

## Contributing

Contributions to Snackify are welcome. Please feel free to fork the repository, make your changes, and submit a pull request.

Built with love by the folks that brought you [Create Expo Stack](https://createexpostack.com/).

## License

This project is licensed under the [MIT License](https://opensource.org/license/mit/).
