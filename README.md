# Structus

Structus is an open-source initiative around **Explicit Architecture**: designing software systems with clear boundaries, explicit intent, and predictable change.

## What we mean by “Explicit Architecture”

- **Clear boundaries:** Separate domain, application/use-cases, infrastructure, and delivery (API/CLI/UI) so each part evolves independently.
- **Domain-first modeling:** Put the business language and invariants at the center of the codebase.
- **Predictable change:** Make changes easy to reason about by keeping responsibilities explicit and dependencies directional.
- **Scalable patterns:** Apply proven architecture patterns (Clean Architecture, CQRS, DDD, event-driven design) without turning them into ceremony.

## Projects

- **Structus Kotlin**  
  Core library implementing Structus building blocks in Kotlin.  
  https://github.com/structus-io/structus-kotlin

- **Structus Kotlin Examples (planned/optional)**  
  Companion examples and reference implementations.  
  https://github.com/structus-io/structus-kotlin-examples

## Current focus

- **Practical architecture building blocks:** Components that make boundaries and responsibilities explicit.
- **Patterns that stay maintainable:** CQRS, DDD, and event-driven workflows applied with pragmatism.
- **Developer experience:** Clear APIs, sensible defaults, and real-world examples.

## Contributing

Contributions are welcome:

- **Issues:** Bug reports, feature requests, and proposals  
  https://github.com/structus-io/structus-kotlin/issues
- **Discussions:** Questions, ideas, and design feedback  
  https://github.com/structus-io/structus-kotlin/discussions
- **Pull requests:** Improvements, fixes, and new features  
  Start with the repository’s CONTRIBUTING guide when available.

## Release philosophy

- **Semantic Versioning:** We aim to follow SemVer for public APIs.
- **Stability:** While versions are `0.x`, APIs may evolve; we’ll document changes clearly and keep upgrades reasonable.

## License

 Everything here is under MIT licence, so feel free to play with it.

---
If you like Structus, consider starring the repositories you use and sharing feedback—it directly helps shape the project.
