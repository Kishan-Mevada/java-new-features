# Java Features by Version (Java 25 to Java 5)

An organized, evolving collection of Java language and platform features introduced in every major release from Java 25 (2025) to Java 5 (2004). Each section includes a brief description and will link to detailed examples and explanations as the repository develops.

---

## Purpose

- **Discover:** Each release’s most notable features, with concise, original descriptions.
- **Learn by Example:** [Upcoming] See practical code for each feature.
- **Deep Dive:** [Upcoming] Explore usage, gotchas, and implementation tips per feature/version.

_contributions, issues, and suggestions are welcome!_

---

## 📂 Table of Contents

- [Java 25 (2025)](#java-25-2025)
- [Java 24 (2024)](#java-24-2024)
- [Java 23 (2024)](#java-23-2024)
- [Java 22 (2023)](#java-22-2023)
- [Java 21 (2023), LTS](#java-21-2023-lts)
- [Java 20 (2023)](#java-20-2023)
- [Java 19 (2022)](#java-19-2022)
- [Java 18 (2022)](#java-18-2022)
- [Java 17 (2021, LTS)](#java-17-2021-lts)
- [Java 16 (2021)](#java-16-2021)
- [Java 15 (2020)](#java-15-2020)
- [Java 14 (2020)](#java-14-2020)
- [Java 13 (2019)](#java-13-2019)
- [Java 12 (2019)](#java-12-2019)
- [Java 11 (2018, LTS)](#java-11-2018-lts)
- [Java 10 (2018)](#java-10-2018)
- [Java 9 (2017)](#java-9-2017)
- [Java 8 (2014, LTS)](#java-8-2014-lts)
- [Java 7 (2011)](#java-7-2011)
- [Java 6 (2006)](#java-6-2006)
- [Java 5 (2004)](#java-5-2004)

---
## Feature Index by Java Version

## Java 25 (2025)
- **Compact Source Files & Instance Main Methods:** Allows simple Java programs without explicit classes.
- **Module Import Declarations:** Import all packages from a module in a single statement.
- **Flexible Constructor Bodies:** Run logic before superclass constructors for safer object creation.
- **Primitive Types in Patterns, `instanceof`, and `switch` (Preview):** Direct pattern matching for primitives.
- **Structured Concurrency (5th Preview):** Group related tasks for easier concurrent management.
- **Scoped Values:** Securely pass immutable values along threads for concurrency.
- **Vector API (10th Incubator):** Boosts performance for data-parallel math operations.
- **Key Derivation Function API:** Modern cryptographic key generation.
- **Compact Object Headers:** Reduces memory use for applications with many small objects.
- **Stable Values (Preview):** Lazily-initialized, immutable values with thread safety.
- **JFR Cooperative Sampling and Method Tracing:** Finer-grained profiling control for better performance analysis.

## Java 24 (2024)
- **Pattern Matching for Primitives:** Concise and type-safe handling of primitives in pattern checks.
- **Better Constructor Logic:** Clearer and safer construction process.
- **Simplified Module Imports:** Streamlined bringing of module packages into scope.
- **Stream Gatherers:** Custom ways to accumulate stream results.
- **Scoped Values & Structured Concurrency (Previews):** Enhanced mechanisms for thread-local data and parallel tasks.
- **Quantum-Safe Cryptography:** Algorithms designed to resist quantum attacks.
- **Class-File API, AOT Loading & Linking:** New tools for bytecode and code loading.

## Java 23 (2024)
- **Richer Pattern Matching for Primitives:** Simplifies code using patterns on primitive types.
- **Improved Switch Patterns:** Match records, arrays, and more in switches.
- **Virtual Threads advancements:** Further optimizations for lightweight concurrency.

## Java 22 (2023)
- **Record Patterns:** Decompose records inline for simpler code.
- **Further Virtual Thread improvements:** Robust support for many lightweight threads.
- **Foreign Function & Memory API:** Simplified, safe access to native memory and code.
- **Unnamed Patterns & Variables:** Ignore unused data in pattern matching.
- **Multi-File Source Execution:** Run multiple source files at once.
- **Code Before `super(…)` (Preview):** Fewer restrictions in constructor logic order.

## Java 21 (2023, LTS)
- **Pattern Matching for `instanceof`:** Reduces need for explicit casting after type checks.
- **Record Patterns (Stable):** Nested decomposition of record data.
- **Improved Records & Enums:** Enhanced definition and use patterns for record/enums.
- **Structured Concurrency (Preview):** Group tasks for shared success or failure.
- **Scoped Values (Preview):** Pass read-only values deeply and safely.
- **String Templates (Preview):** Simplifies and secures string creation.
- **Deprecated Security Manager:** Removal of dated security model.

## Java 20 (2023)
- **Unveiled Record Patterns (Preview):** Streamlined record component extraction.
- **Switch Patterns:** More capable, streamlined switch statements.
- **Foreign Function & Memory API updates:** Enhanced safe calls to non-Java code.
- **Virtual Threads & Structured Concurrency:** Better concurrency primitives for scalable apps.
- **Unicode 15.0 Support:** Updated international character set support.

## Java 19 (2022)
- **Record and Switch Patterns (Preview):** More flexible, concise coding with patterns.
- **Foreign Memory & Function API (Preview):** Easier native library connectivity.
- **Virtual Threads:** Streamlined massive task concurrency.
- **Structured Concurrency:** Fewer errors in parallel work units.
- **Vector API (Incubator):** Emerging support for parallel math workloads.

## Java 18 (2022)
- **UTF-8 Default Charset:** Reliable UTF-8 across platforms.
- **Simple Web Server:** Quick, temporary HTTP server for local testing.
- **Code in API Docs:** Live code examples in Javadoc.
- **Switch Pattern Previews:** Broader use of pattern matching in switch.
- **Gradual Deprecation of Finalization:** Move away from finalizer-based cleanup.

## Java 17 (2021, LTS)
- **Sealed Classes:** Restrict permissible subclasses for stronger APIs.
- **Pattern Matching for Switch (Preview):** Powerful, concise switch syntax.
- **Enhanced Random Number Generators:** More robust and flexible randomness.
- **Foreign Function & Memory API (Incubator):** Improve Java-native code bridge.
- **Context-Specific Serialization Filters:** Safer object serialization.

## Java 16 (2021)
- **Records (Stable):** Concise, immutable data classes.
- **Pattern Matching for `instanceof`:** No need to cast after checking type.
- **Sealed Classes (Preview):** Early feature for limiting subclassing.

## Java 15 (2020)
- **Text Blocks:** Readable multi-line strings.
- **Sealed Classes (Preview):** Precise control over inheritance.
- **Hidden Classes:** Dynamic frameworks can define non-discoverable classes.

## Java 14 (2020)
- **Switch Expressions:** Switch that returns values.
- **Record Classes (Preview):** Initial release of concise data holders.
- **Pattern Matching for `instanceof` (Preview):** Cleans up instance type-checks.
- **Helpful NullPointerExceptions:** Reveals the root cause in null pointer errors.

## Java 13 (2019)
- **Text Blocks (Preview):** Previews multi-line string handling.
- **Dynamic CDS Archives:** Share class metadata at runtime for faster starts.

## Java 12 (2019)
- **Switch Expressions (Preview):** Early switch with value-return.
- **New Garbage Collection Tuning:** More memory management flexibility.

## Java 11 (2018, LTS)
- **Local-Variable `var` for Lambdas:** Less code for type declarations in lambdas.
- **Run Source Code Directly:** Top-level Java file execution without compilation step.
- **HTTP Client Standardization:** Modern HTTP client built into the platform.
- **More String Methods:** Utilities for string handling, e.g., strip, repeat.

## Java 10 (2018)
- **Local Variable Type Inference with `var`:** Cleaner, less repetitive local variable syntax.
- **Application Class Data Sharing:** Share class metadata over JVMs, saves memory.
- **Faster G1 GC:** Improved garbage collection speed.

## Java 9 (2017)
- **Modular System:** Modularization for scalable, maintainable applications.
- **JShell:** Interactive Java REPL shell.
- **Private Interface Methods:** Encapsulate logic within interfaces.
- **Collection Factory Methods:** Quick creation of immutable collections.

## Java 8 (2014, LTS)
- **Lambda Expressions:** Functionals bring concise, expressive code.
- **Stream API:** Efficient, pipeline-based data handling.
- **Default & Static Methods:** Interfaces with common implementations.
- **Modern Date/Time API:** Robust, reliable date/time solution.
- **CompletableFuture API:** Simple async programming patterns.

## Java 7 (2011)
- **Strings in Switch:** Use strings in switch-case lists.
- **Diamond Operator:** Simplifies type declarations with generics.
- **Automatic Resource Management:** Cleanup resources automatically with try-with-resources.
- **Multi-Catch, Precise Rethrow:** More efficient exception handling.

## Java 6 (2006)
- **Scripting Support:** Native support for running scripts via JSR 223.
- **Web Services APIs:** Better connection to web services across platforms.
- **JDBC 4.0, JAXB 2.0:** Enhanced data and XML integration.
- **Compiler API:** Programmatic access to Java compilation.

## Java 5 (2004)
- **Generics:** Type-safe, reusable code components.
- **Annotations:** Add metadata to code for tools and frameworks.
- **Autoboxing/Unboxing:** Automatic conversion between primitives and objects.
- **Enhanced for-each Loop:** Simple looping through collections.
- **Enumerated Types:** Built-in support for type-safe constants.
- **Varargs, Static Imports, Concurrency Utilities:** Flexible parameters, easier imports, and modern threading tools.

---

## How to Use This Repo

1. **Browse the Features:** Peek at the list above to discover new and recent Java platform features.
2. **Read Descriptions:** Each item is a short, original summary for quick orientation.
3. **See Example & Guide:** (To be developed) Click `[Examples & Explanation]` to dive into hands-on demos and deeper reading.
4. **Contribute:** Add a code example, clarify a tricky bit, open an issue, or submit PRs for missing features.

---

## Contributing

We welcome pull requests! Follow the template file `_template.md` for writing new examples:
- **Feature:** Short name
- **Since Java:** Version
- **Short Description:** 1–2 lines
- **Explanation:** More detail, possible edge cases
- **Example:** Valid code snippet
- **References:** Official JEP docs, etc. (where possible)

> Place feature file in javaXX/feature_name.md  (javaXX is sub module in repo)

---

## License

[MIT](LICENSE)

---

> This repo is a living document. Check back or watch for updates as new Java releases drop and expanded explanations/examples are added.