# Contributing

Start with the relevant repository's issues and development instructions. For substantial architecture or API changes, describe the intended behavior, scope, and validation before implementation.

## Physics and rendering changes

- State units, assumptions, material parameters, and boundary conditions.
- Include a reproducible scenario and expected behavior.
- Validate numerical changes against analytical, experimental, or established reference results where appropriate; state tolerances and limitations.
- Explain conservation or dissipation behavior and timestep/resolution sensitivity.
- For rendering changes, provide comparable images and describe the visual difference.
- For performance claims, record hardware, workload, build configuration, and completed-work timings.

## Pull requests

Keep changes focused. Link the relevant issue, explain the resulting behavior, and report the checks actually run. Follow repository-specific instructions; for Rust changes, run applicable formatting, lint, and test checks. Document failures and unavailable checks rather than claiming success.
