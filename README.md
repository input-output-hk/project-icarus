# Project Icarus 

Icarus, a reference implementation for a lightweight wallet, which will enable developers to create their own wallets for Cardano. Icarus runs in a browser as a Google Chrome extension and offers an easy-to-use alternative to Daedalus. This wallet does not need to download and validate a copy of the Cardano blockchain, instead, it uses a copy of the blockchain on a server, so it offers advantages in terms of speed of use. Icarus is secure – private keys are encrypted on the user's machine and not shared with servers. Releasing the source code will mean the community can develop wallets and integrate with Cardano as required and Cardano moves further towards decentralisation.

## Getting started

This project is structured in trhee sides: the backend, the importer and the chrome extension

### Backend development

To build the backend, install [Docker](https://www.docker.com/get-started) and docker-compose.

Once this is done, run `docker-compose up` to build and start the backend locally.

### Importer development

Please refer to the follwing [README](https://github.com/input-output-hk/project-icarus-importer/blob/icarus-master/blockchain-importer/README.md)

### Chrome extension development

Everything is described in [chrome-extension/](https://github.com/input-output-hk/project-icarus-chrome/blob/master/README.md)

## Project layout

* [backend/](https://github.com/input-output-hk/project-icarus-backend-service) - the source of the backend webapp
* [importer/](https://github.com/input-output-hk/project-icarus-importer) - the chain importer
* [chrome-extension/](https://github.com/input-output-hk/project-icarus-chrome) - the source of the chrome extension


## License

This project is Copyright Copyright (c) 2018 IOHK Ltd. and licensed under the [MIT](LICENSE.md)
