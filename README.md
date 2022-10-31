# nx-ts-esm-loader

Module loader to allow running ESM-targeted node scripts importing from libraries in an NX workspace.

A thin wrapper around ts-node's esm module loader.

## Installation

```
npm i --save-dev nx-ts-esm-loader
```

## Usage

To run script `<SCRIPT>`:

```bash
TS_NODE_PROJECT=<path_to_nx_library_or_app>/tsconfig.lib.json  NX_BASE_TSCONFIG=<path_to_nx_workspace>/tsconfig.base.json node --loader nx-ts-esm-loader <SCRIPT>
```
