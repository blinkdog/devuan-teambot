# devuan-teambot
Go Team Robot

## Development
To set up a development environment for `devuan-teambot`:

    git clone https://github.com/blinkdog/devuan-teambot
    cd devuan-teambot
    npm install
    node_modules/.bin/cake rebuild

The source files are located in `src/main/coffee`.
The test source files are located in `src/test/coffee`.

To rebuild the project:

    node_modules/.bin/cake rebuild

To view test coverage:

    node_modules/.bin/cake coverage

To check if any npm provided dependencies are out of date:

    node_modules/.bin/cake check
