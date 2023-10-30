# Install Foundry

```sh
curl (-k) -L https://foundry.paradigm.xyz | bash
```

Running `foundryup` by itself will install the latest (nightly) precompiled binaries: `forge, cast, anvil, and chisel`. 
See `foundryup --help` for more options, like installing from a specific version or commit.

```sh
foundryup
```

To start a new project with Foundry, use `forge init`

```sh
forge init hello_foundry
```