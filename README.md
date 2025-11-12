# rusty-mp3
Simple mp3 player written in Rust for learning purposes

## Project Structure

- `src/` - Source code for the MP3 player
- `tests/` - Integration and unit tests
- `docs/` - Project documentation in reStructuredText format

## Building

This project uses Bazel as its build system. To build the project:

```bash
bazel build //src:rusty-mp3
```

## Running

To run the MP3 player:

```bash
bazel run //src:rusty-mp3
```

## Testing

To run the tests:

```bash
bazel test //tests:all
```

## Documentation

See the `docs/` directory for detailed documentation:
- `docs/index.rst` - Main documentation
- `docs/architecture.rst` - Architecture overview
