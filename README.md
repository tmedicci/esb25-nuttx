
# Espressif Summit Brazil 2025 - Python on NuttX: New Possibilities for Embedded Systems

This repository contains the slide deck for the `Python on NuttX: New Possibilities for Embedded Systems` presentation on Aug 5th, 2025 in Campinas, Brazil.

This presentation was built using `Slidev`. [Slidev](https://sli.dev/) is a web-based slides maker and presenter. It's designed for developers to focus on writing content in Markdown.

## Installation and configuration

You can use your OS native package manager to install the dependencies, however, it is recommended to use `nvm` -- Node.js version manager.

The following instructions are provided in detail, as parts of the Node.js ecosystem may not be immediately intuitive to some users. These steps have been tested on Linux only. The general approach should be similar on other operating systems with some possible adjustments.

### Software dependencies

Slidev requires `Node.js`, which can be conveniently installed using [nvm](https://github.com/nvm-sh/nvm?tab=readme-ov-file#installing-and-updating):

```sh
# Install nvm
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash
source ~/.nvm/nvm.sh
# Install Node.js (LTS version includes npm)
nvm install --lts
```

## Usage

To run this presentation locally:

1. Clone this repo:
    ```sh
    git clone https://github.com/tmedicci/esb25-nuttx.git
    cd esb25-nuttx
    ```
2. Install project dependencies:
    ```sh
    npm install
    ```

To start the slide show:

- Run `slidev`
- Visit <http://localhost:3030>
