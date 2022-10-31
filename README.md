# nx-ts-esm-loader

Module loader to allow running ESM-targeted node scripts importing from libraries in an NX workspace.

A thin wrapper around ts-node's esm module loader.

## Usage

```bash
TS_NODE_PROJECT=<path_to_nx_library_or_app>/tsconfig.lib.json  NX_BASE_TSCONFIG=<path_to_nx_workspace>/tsconfig.base.json node --loader ./loader.mjs <script_to_run>
```
