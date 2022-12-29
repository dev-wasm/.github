# Devcontainers for WASM
This is a collection of [devcontainers](https://containers.dev/) which are intended to make it easier to get started with
WebAssembly (WASM) and WebAssembly System Interface (WASI) development in a variety of different programming languages.

Currently, containers are available for:
* [C/C++](https://github.com/dev-wasm/dev-wasm-c)
* [Dotnet](https://github.com/dev-wasm/dev-wasm-dotnet)
* [Go](https://github.com/dev-wasm/dev-wasm-go)
* [Pascal](https://github.com/dev-wasm/dev-wasm-pascal)
* [Python](https://github.com/dev-wasm/dev-wasm-python)
* [Rust](https://github.com/dev-wasm/dev-wasm-rust)
* [AssemblyScript/TypeScript](https://github.com/dev-wasm/dev-wasm-ts)
* [Zig](https://github.com/dev-wasm/dev-wasm-zig)

# Usage
Devcontainers are development environments for Github Codespaces and Visual Studio Code (and possibly other) places.
Each devcontainer contains all of the tools necessary to immediately start developing. Additionally, these devcontainers
also contain some sample code to get started.

To use a devcontainer simply go to the particular language you are interested in an follow the instructions in the README.

If you run into problems, please file an issue on that particular repository.

# Status
These containers work correctly, but in many cases they are pretty minimal environments and as you try to do
more sophisticated things, it may not work correctly. File bugs! In general WASM + WASI is still in early days
so expect rough edges (but hopefully smoother edges soon!)

# Who is behind this?
Currently this is a hobby project of Brendan Burns (@brendandburns). Hopefully there will be more folks in the future.

# Acknowledgements
Much of this is a collection of hard work from others in the WASM/WASI community. This repo is largely the "last mile"
to collect it together and make it easy to use.

# How can I run this somewhere other than a codespace?
If you are interested in doing more with WASM, please checkout [how to run WASM/WASI containers in Kubernetes](https://learn.microsoft.com/en-us/azure/aks/use-wasi-node-pools)
