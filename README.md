pouchdb-adapter-rn-websql-core ![semver non-compliant](https://img.shields.io/badge/semver-non--compliant-red.svg)
======

Underlying adapter code for apps built using ReactNative and SQLite-based PouchDB adapters.



### Prerequisites

- [pouchdb-react-native](https://github.com/stockulus/pouchdb-react-native)
- [react-native-fetch-blob](https://github.com/kkbhav/react-native-fetch-blob)
  
### Usage

```bash
npm install --save-exact pouchdb-adapter-rn-websql-core
npm install --save pouchdb-react-native
npm install --save https://github.com/kkbhav/react-native-fetch-blob.git
react-native link react-native-fetch-blob
```

For full API documentation and guides on PouchDB, see [PouchDB.com](http://pouchdb.com/). For details on PouchDB sub-packages, see the [Custom Builds documentation](http://pouchdb.com/custom.html).

### Warning: semver-free zone!

This package is conceptually an internal API used by PouchDB or its plugins. It does not follow semantic versioning (semver), and rather its version is pegged to PouchDB's. Use exact versions when installing, e.g. with `--save-exact`.


