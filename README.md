# Event-Integrator CLI

Command-line interface for Event-Integrator - A powerful event management and processing platform.

## Overview

The Event-Integrator CLI provides a streamlined interface for managing, configuring, and monitoring Event-Integrator deployments. It enables developers to interact with the Event-Integrator runtime, manage event processing rules, and debug event flows from the command line.

## Key Features

- **Configuration Management**: Create, validate, and manage Event-Integrator configurations
- **Event Processing**: Submit, monitor, and manage events in the processing pipeline
- **Debugging**: Inspect event payloads, traces, and execution logs
- **Health Checks**: Monitor system health and connection status
- **Automation**: Integrate with CI/CD pipelines and automation workflows

## Installation

```bash
# Via Homebrew
brew install event-integrator

# Via Go
go install github.com/similigh/event-integrator-cli@latest

# From source
git clone https://github.com/similigh/event-integrator-cli
cd event-integrator-cli
go build -o event-integrator ./cmd
```

## Quick Start

```bash
# Initialize configuration
event-integrator init

# Validate your configuration
event-integrator validate config.yaml

# Submit an event
event-integrator event send --file event.json

# Monitor event processing
event-integrator event watch
```

## Documentation

- [Getting Started Guide](docs/getting-started.md)
- [Configuration Reference](docs/configuration.md)
- [Command Reference](docs/commands.md)
- [Examples](examples/)

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on how to contribute to this project.

## License

MIT License - see LICENSE file for details
