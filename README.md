# ShipFlow — Simplify Software Delivery

ShipFlow is a software delivery automation platform that helps developers build, test, and deploy applications through consistent, reusable workflows. It is designed to run across local development environments, continuous integration (CI) systems, and cloud infrastructure.

By combining containerized execution, programmable workflows, and intelligent caching, ShipFlow aims to make software delivery more reliable, efficient, and easier to maintain.

## Installation

```bash
brew install dagger/tap/dagger
```

> Note: This installation command still installs the original Dagger CLI. Replace it only after creating and publishing your own implementation or providing the correct installation method.

## Why ShipFlow?

### Programmable Automation

Create reusable software delivery workflows using code and structured APIs instead of relying entirely on shell scripts or platform-specific configuration files. Language SDKs and reusable modules help organize complex automation tasks.

### Consistent Across Environments

Run workflows on local machines, CI servers, or cloud infrastructure. Container-based execution helps maintain consistent dependencies and behavior across supported environments.

### Efficient and Repeatable Execution

Define dependencies explicitly and execute operations in isolated containers. Incremental execution and content-based caching help avoid repeating work when inputs have not changed.

### Transparent Workflow Execution

Inspect logs, metrics, and distributed traces to understand how each operation runs. OpenTelemetry integration supports debugging, performance analysis, and exporting trace data to compatible observability tools.

## Key Features

### Unified System API

Work with containers, filesystems, secrets, Git repositories, network tunnels, and other resources through composable, typed operations.

### Multi-Language SDKs

Build automation workflows using:

- Go
- Python
- TypeScript
- PHP
- Java
- .NET
- Elixir
- Rust

### Typed Artifacts

Create custom types that combine state and functionality, allowing structured objects to be reused across compatible modules and SDK boundaries.

### Incremental Execution and Caching

Track operation inputs and reuse cached results whenever possible. When a dependency changes, only affected operations need to be executed again.

### Cross-Platform Compatibility

Run natively on Linux or use compatible container environments on macOS and Windows. A supported Linux container runtime is required.

### Observability and Tracing

Monitor workflow execution through terminal-based interfaces and web views. Export OpenTelemetry traces to compatible platforms such as Jaeger and Honeycomb.

## Getting Started

Begin with a simple workflow and gradually expand it to automate your application's build, testing, and deployment processes.

- [Documentation](https://docs.dagger.io)
- [Quickstart Guide](https://docs.dagger.io/quickstart)

ShipFlow provides a foundation for building repeatable delivery workflows that can evolve alongside your software projects.