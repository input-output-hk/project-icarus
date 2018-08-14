# Icarus

Icarus is a reference implementation for a lightweight wallet developed by the
IOHK Engineering Team. This code base can be used as a point of reference to
enable developers to create their own secure light and mobile wallets for
Cardano.  Icarus is a fully open-source code base that will be the first step
in a range of open source initiatives to provide developers with a suite of
tools to integrate with Cardano.

## Getting started

This project is structured in trhee sides: the backend, the importer and the chrome extension

### Backend development

To build the backend, install [Docker](https://www.docker.com/get-started) and docker-compose.

Once this is done, run `docker-compose up` to build and start the backend locally.

### Importer development

Please refer to the follwing [README](https://github.com/atixlabs/project-icarus-importer/blob/icarus-master/blockchain-importer/README.md)

### Chrome extension development

Everything is described in [chrome-extension/](chrome-extension/#readme)

## Project layout

* [backend/](backend/#readme) - the source of the webapp
* [cardano-sl/](cardano-sl/#readme) - the chain importer
* [chrome-extension/](chrome-extension/#readme) - the source of the chrome extension


## License

This project is Copyright 2018 IOHK and licensed under the [MIT](LICENSE.md)
