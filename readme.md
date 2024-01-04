# Personal Neovim Configuration

This Neovim configuration is designed for a personalized and efficient coding experience. It is written in Lua and based on NvChad, offering features such as auto-formatting on save, language server support for JavaScript, TypeScript, React, and Tailwind CSS integration.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Plugins](#plugins)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Auto-formatting on Save**: Ensure code consistency by automatically formatting code on save.
- **Language Server Support**: Intelligent code completion and error checking for JavaScript, TypeScript, and React.
- **Tailwind CSS Integration**: Support for Tailwind CSS development.

## Prerequisites

Before you start, make sure you have the following installed:

- Neovim (nightly version recommended)
- Node.js (for JavaScript and TypeScript support)
- `eslint`, `prettier`, and other necessary language tools globally installed.

## Installation

1. **Clone Repository**:

   ```bash
   git clone https://github.com/dityaren/nvim.git ~/.config/nvim
   ```

   Mason will automatically install all the required plugins when you open Neovim.

## Usage

1. **Open Neovim**:

   ```bash
   nvim
   ```

2. **Enjoy Coding**:

   Start coding with the enhanced features and configurations.

## Customization

Feel free to customize the configuration according to your preferences. Edit the `./lua/custom/plugins.lua` file to add or modify settings. Explore Neovim documentation for more customization options.

## Plugins

This configuration includes the following plugins:

- [NvChad](https://github.com/NvChad/NvChad): The base configuration for Neovim.
- [nvim-lspconfig](https://github.com/neovim/nvim-lspconfig): A plugin for configuring language servers.

Feel free to explore and add more plugins to suit your needs.

## Contributing

Contributions are welcome! If you have improvements or additional features to suggest, please create a pull request.

## License

This Neovim configuration is open-source and available under the [GNU GENERAL PUBLIC LICENSE](LICENSE). Feel free to use and modify it according to your needs.
