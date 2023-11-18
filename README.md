# Link Validator

## Description

The Link Validator is a Node.js program that allows users to validate links in a given text file or directory. It checks the status of each link and provides information about their validity.

## Features

- **Validate Links**: Check the status of links to ensure they are valid and reachable.

- **Support for Files and Directories**: Validate links in a single text file or in all text files within a directory.

## Technologies Used

- **Node.js**: Powers the backend of the application.

- **chalk**: Adds color to the console output for a better user experience.

## Usage

To use the Link Validator, run the following command:

```bash
node cli.js <file-or-directory-path> [--valida]
```
* '<file-or-directory-path>': The path to the text file or directory containing the text files.

* --valida: An optional flag to perform link validation. If not provided, the CLI will display the list of links without validation.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/link-validator-cli.git
```

2. Install dependencies:

```bash
npm install
```

## Commands
* Validating Links:

```bash
node cli.js <file-or-directory-path> --valida
```

* Displaying Links:

```bash
node cli.js <file-or-directory-path>
```

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.
