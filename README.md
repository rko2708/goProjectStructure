# goProjectStructure

A basic Go project boilerplate structure.

## Prerequisites

- Go 1.25.6 or higher

## Project Structure

- `cmd/`: Main applications for this project.
- `internal/`: Private application and library code.
- `tests/`: Additional external test applications and test data.
- `bin/`: Compiled executable binaries.
- `MakeFile`: Makefile with convenient commands to build, run, and test.

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/rko2708/goProjectStructure.git
cd goProjectStructure
```

### Build

To compile the application, use the provided Makefile target:

```bash
make build
```

This will output the compiled binary to `bin/main`.

### Run

To run the application directly:

```bash
make run
```

### Test

To execute all the tests in the project:

```bash
make test
```

### Clean

To remove the compiled binaries:

```bash
make clean
```
