# RunCLI

RunCLI is a lightweight open-source command runner powered by `.run` files.

## Features

- Simple command execution
- Lightweight and fast
- Cross-platform design
- Open source (MIT License)
- Easy installation

## Example

### .run

```text
hello : echo Hello World

build : dotnet build

start : dotnet run
```

### Usage

```bash
run hello
run build
run start
```

## Installation

### macOS

Download:

```text
Run.pkg
```
- Double click on Run.pkg

Install and use:

```bash
run hello
```

## Project Structure

```text
RunCLI
├── run
├── Run.pkg
└── LICENSE
```

## License

MIT License