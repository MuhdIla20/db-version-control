# db-version-control 🚀

![Version Control](https://img.shields.io/badge/Version%20Control-WordPress%20to%20JSON-blue)

Welcome to the **db-version-control** repository! This project helps you sync your WordPress database with version-controlled JSON files, making it easier to manage changes and collaborate with others using Git workflows.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Support](#support)

## Introduction

Managing a WordPress site often involves frequent updates to the database. Keeping track of these changes can be challenging. The **db-version-control** project provides a solution by exporting your WordPress database to JSON files. This allows you to version control your database changes using Git, making collaboration and tracking much easier.

## Features

- **Sync WordPress to JSON**: Easily export your WordPress database to JSON files.
- **Version Control**: Use Git to track changes to your database over time.
- **Collaboration Friendly**: Work seamlessly with teams using Git workflows.
- **Easy Setup**: Simple installation and usage instructions.

## Installation

To get started with **db-version-control**, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/MuhdIla20/db-version-control.git
   ```

2. Navigate to the project directory:
   ```bash
   cd db-version-control
   ```

3. Install the required dependencies:
   ```bash
   npm install
   ```

4. Configure your WordPress settings as needed.

## Usage

After installation, you can start using the tool to sync your WordPress database with JSON files. 

1. Run the script to export your database:
   ```bash
   npm run export
   ```

2. Your database will be saved as JSON files in the `exports` directory.

3. To import changes back to WordPress, use:
   ```bash
   npm run import
   ```

For detailed instructions and options, please refer to the documentation within the repository.

## Releases

To download the latest version of **db-version-control**, visit the [Releases](https://github.com/MuhdIla20/db-version-control/releases) section. Make sure to download the appropriate files and execute them as needed.

## Contributing

We welcome contributions to improve **db-version-control**! If you have suggestions, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your branch and create a pull request.

Please ensure your code follows the existing style and includes tests where applicable.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Support

If you have any questions or need support, please check the [Releases](https://github.com/MuhdIla20/db-version-control/releases) section or open an issue in the repository. We appreciate your feedback!

---

Thank you for checking out **db-version-control**! We hope this tool helps streamline your WordPress development process. Happy coding!