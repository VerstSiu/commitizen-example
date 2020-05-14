
# Commitizen Example

[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)

Required Environments:

* Node 10 or 12
* npm 6+

## Get Start

* Install `Node.js`:

    ```bash
    brew install node

    # Check installed versions
    node -v
    npm -v

    # Update
    brew update node

    # Uninstall
    brew uninstall node
    ```

* Install command line tool:

    ```bash
    npm install -g commitizen
    ```

* Initialize project to use the cz-conventional-changelog adapter:

    ```bash
    commitizen init cz-conventional-changelog --save-dev --save-exact

    # Yarn
    commitizen init cz-conventional-changelog --yarn --dev --exact
    ```

## Conventional commit messages as a global utility

* Install your preferred `commitizen` adapter globally:

    ```bash
    npm install -g cz-conventional-changelog
    ```

* Create a `.czrc` file in your `home` directory, with `path` referring to the preferred, globally installed, `commitizen` adapter:

    ```bash
    echo '{ "path": "cz-conventional-changelog" }' > ~/.czrc
    ```

* Commit your changes:

    ```bash
    git cz
    ```

## Reference

* [Commitizen for contributors](https://github.com/commitizen/cz-cli)
* [conventional-changelog](https://github.com/conventional-changelog/conventional-changelog)
* [Node.js](https://nodejs.org/)