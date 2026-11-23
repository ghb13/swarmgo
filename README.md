# swarmgo

Coordinating AI agents requires a way to define their tasks and control how they interact. swarmgo is a Go package for AI agent coordination and task execution, based on the SwarmGo project inspired by OpenAI's Swarm framework.

## Features

- Create AI agents in Go to carry out tasks.
- Coordinate interactions between agents.
- Control agent execution from Go application code.

## Installation

**Publication details are not yet specified.** Replace `YOUR_GITHUB_OWNER` with this standalone project's GitHub owner. The commands below assume the repository uses that module path; the archive command also requires a published release with the matching asset name.

From your Go application directory:

```sh
go get github.com/YOUR_GITHUB_OWNER/swarmgo
```

To download the source release archive for `v0.1.0`:

```sh
curl -fL -o swarmgo-v0.1.0.tar.gz https://github.com/YOUR_GITHUB_OWNER/swarmgo/archive/refs/tags/v0.1.0.tar.gz
```

## Usage

**swarmgo is a package, not a documented command-line application.** The supplied project information does not establish exported API names or CLI arguments, so an agent-execution example would require assumptions.

After checking out the standalone repository, run its Go package tests with verbose output and test caching disabled:

```sh
cd swarmgo
go test ./... -v -count=1
```

This command runs tests; it does not launch an agent. Application-level examples should use the package's verified API once that API is available.

## License

MIT. This project is based on [prathyushnallamothu/swarmgo](https://github.com/prathyushnallamothu/swarmgo). Retain the upstream copyright notice and MIT permission notice in copies or substantial portions of the original software.

## Related projects

The following repositories were supplied as related projects. Their functionality and common authorship were not established by the supplied project information.

- [pmamediajogja-cyber/gantryd](https://github.com/pmamediajogja-cyber/gantryd): No project description was provided.
- [EngHirsi/wg-access-server](https://github.com/EngHirsi/wg-access-server): No project description was provided.
- [khuram-bti/taskomask](https://github.com/khuram-bti/taskomask): No project description was provided.

