# Quick Till Point of Sale

![POS](screenshots/quicktill_pos.png)

Desktop Point of Sale app built with electron

**Features:**

- Can be used by multiple PC's on a network with one central database.
- Receipt Printing.
- Search for product by barcode.
- Staff accounts and permissions.
- Products and Categories.
- Basic Stock Management.
- Open Tabs (Orders).
- Customer Database.
- Transaction History.
- Filter Transactions by Till, Cashier or Status.
- Filter Transactions by Date Range.
- Generate & print barcodes for each product

## Development

Quicktill is an offline-first application built on jQuery, Node, and Electron. It utilizes a local NeDB as the database by default.

### Pre-requisites

To get the dev environment up and running you need to first set up Node.js version
16.14.0 or greater and npm. For this, we suggest using
[nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

Next, you will need to install [yarn](https://classic.yarnpkg.com/lang/en/docs/install/#mac-stable).

### Clone and Run

Once you are through the Pre-requisites, you can run the following commands to
setup Quicktill for development and building:

```bash
# clone the repository
git clone https://github.com/Ayuen-madyt/Quicktill.git

# change directory
cd Quicktill

# install dependencies
yarn
```

#### Development

To run Quicktill in development mode:

```bash
# start the electron app
yarn electron
```

#### Build

To build Frappe Books and create an installer:

```bash
# start the electron app
yarn electron-build
```

**Note: Build Target**
By default the above command will build for your computer's operating system and
architecture. To build for other environments (example: for linux from a windows
computer) check the _Building_ section at
[electron.build/cli](https://www.electron.build/cli).

### Project Contribution Guidelines

Thank you for your interest in contributing to Quicktill POS! This document outlines the guidelines for contributing to our repository. Please take a moment to read through this guide before making any contributions. By following these guidelines, you will help us maintain a high-quality codebase and ensure a smooth contribution process.

### Branching

- Create a new branch for each significant contribution or bug fix.
- Choose a descriptive name for your branch that reflects the purpose of your changes.-
- To create a new branch: git checkout -b branch-name.

### Development Workflow

- Fork the repository first.
- Familiarize yourself with the project's technology stack, including jQuery, Node, and Electron.
- Make your code changes, following the existing coding style and conventions.
- Test your changes thoroughly, ensuring they work seamlessly with Quicktill's offline functionality.
- Commit your changes with a clear and descriptive commit message.
- Push your changes to your forked repository.
- Open a pull request (PR) from your branch to the master branch of the main repository.

### Pull Request Guidelines

- Each PR should have a clear and descriptive title.
- Include a concise summary of the changes made in the description.
- Provide any relevant information or context that may help reviewers understand the purpose and impact of the changes.

### Background of this project

The Quicktill project has a notable background that demonstrates its origin and the motivation behind its development. Initially, I would like to express my gratitude to [tngoman](https://github.com/tngoman/Store-POS.git) for their valuable contribution to the original repository located at [https://github.com/tngoman/Store-POS.git](https://github.com/tngoman/Store-POS.git). The original project created by tngoman has proven to be highly effective and impactful within its domain.

Due to the exceptional qualities and functionalities exhibited by the original Quicktill repository, I made the decision to maintain a forked version of the project. This decision was driven by the recognition of the project's potential to further enhance and provide valuable solutions within the realm of point-of-sale (POS) systems.

By maintaining the forked version of Quicktill, I aim to continue the legacy of the project, fostering its growth and ensuring its longevity. The focus remains on improving the codebase, incorporating new features, enhancing performance, and addressing any reported issues or bugs. Through this endeavor, the intention is to provide a robust and reliable solution that meets the evolving needs of the users and the broader community.

The Quicktill project represents a collaborative effort and welcomes contributions from individuals who share the vision of delivering a comprehensive and efficient POS system. Together, we strive to make Quicktill a leading choice for businesses seeking a reliable and customizable point-of-sale solution.

Thank you to all the contributors, past and present, who have helped shape Quicktill into what it is today. Your dedication and support are invaluable in driving the success of this project.

## License

[GNU Affero General Public License v3.0](LICENSE)
