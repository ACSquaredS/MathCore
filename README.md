# MathCore

Core layer of [MathCraft](https://github.com/ACSquaredS/MathCraft), an open-source, MATLAB-inspired numerical computing environment.

> **Status:** Early stage. The repository is set up; implementation has not started.

## Role in MathCraft

MathCore is the foundation. Every other MathCraft module depends on it. It defines the shared data model (arrays and matrices, scalar and string values, errors) and the contracts that modules use to work together.

## Depends on

Nothing. This is the base layer.

## Planned scope

- Array and matrix type with a defined element type and shape
- Indexing and broadcasting rules
- Error and exception model shared by all modules
- Interfaces that the other modules implement

## Boundaries

Algorithms (solvers, transforms, statistics) do not belong here. They belong in the module that owns their domain.

## Getting started

Not available yet. This section will be filled in with the first release.

## Contributing

Contribution guidelines will be published in the [MathCraft](https://github.com/ACSquaredS/MathCraft) umbrella repository. Until then, open an issue to discuss a change before sending a pull request.

## License

Released under the [MIT License](LICENSE).
