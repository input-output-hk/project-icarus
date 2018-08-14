# Icarus

Meta-repo for the release of the Icarus project. This repository assembles all the pieces needed to create your own fork of Icarus.

Icarus is a reference implementation of the light wallet design.

## Getting started

This project is structured in two sides: the backend and the chrome extension

### Backend development

To build the backend, install [Docker](https://www.docker.com/get-started) and docker-compose.

Once this is done, run `docker-compose up` to build and start the backend locally.

### Chrome extension development

Everything is described in [chrome-extension/](chrome-extension/#readme)

## Project layout

* [backend/](backend/#readme) - the source of the webapp
* [cardano-sl/](cardano-sl/#readme) - the chain importer
* [chrome-extension/](chrome-extension/#readme) - the source of the chrome extension


## License

This project is Copyright 2018 IOHK and licensed under the [MIT](LICENSE.md)
