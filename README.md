# MoonBit CaseKit

Collect observable behavior from MoonBit code and compare runs across compiler backends.
The core library is written in MoonBit and has no external dependencies.

## Collect results

Create a named `Suite`, call `observe` with unique case IDs and JSON-serializable values,
and print `suite.encode()`. The output can be saved by a runner for later comparison.
Non-finite numbers and duplicate IDs are rejected instead of silently losing evidence.

## License

[MIT](LICENSE). This is an independent library, not a fork of a Markdown parser.
