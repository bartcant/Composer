# Sample Hyperledger Composer Business Network Definitions

You must install [Lerna](https://lernajs.io) to build this multi-package repository.

    $ npm install -g lerna

Once Lerna is installed, and this repository is cloned, then you must bootstrap the
repository so that all of the dependencies are installed and all of the packages are
linked together:

    $ lerna bootstrap

You can then work with the packages under [packages/](packages/) on a per-package
basis as any normal node.js package.

Alternatively, you can execute npm commands across all of the packages at once using
Lerna:

    $ lerna run test
