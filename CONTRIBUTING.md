# Contributing to AiLydian Projects

Thank you for your interest in contributing. Most repositories under this account are proprietary enterprise software. Please read this guide before submitting any contributions.

---

## Repository Types

### Proprietary Repositories

Repositories marked with a proprietary license (the majority of our platforms) are **not open for external contributions** without prior written agreement.

By submitting a pull request to a proprietary repository, you agree that:

1. Your contribution becomes the property of AiLydian.
2. You grant a perpetual, worldwide, royalty-free license to use, modify, and distribute your contribution.
3. You have the right to submit the contribution and it does not violate any third-party rights.

### Open-Source Repositories

Repositories with an explicit open-source license — such as **LyTrade Scanner** ([borsa.ailydian.com](https://github.com/lydianai/borsa.ailydian.com)) under MIT — welcome contributions under the terms of that license.

---

## How to Contribute (Open-Source)

### Reporting Bugs

1. Check existing issues to avoid duplicates.
2. Use the **Bug Report** issue template.
3. Include: steps to reproduce, expected behavior, actual behavior, environment details.
4. Attach screenshots, logs, or error messages if applicable.

### Suggesting Features

1. Use the **Feature Request** issue template.
2. Describe the problem the feature would solve.
3. Propose a solution with as much detail as possible.

### Submitting Code

1. Fork the repository.
2. Create a feature branch from :
   
3. Write tests for your changes (minimum 80% coverage for new code).
4. Ensure all tests pass:
   
5. Follow the existing code style and TypeScript strict conventions.
6. Sign your commits (GPG or SSH signing required).
7. Submit a pull request with a clear description referencing any related issues.

---

## Commit Message Format

Follow [Conventional Commits](https://www.conventionalcommits.org/):



**Types:**  ·  ·  ·  ·  ·  ·  · 
 usage: perf [--version] [--help] [OPTIONS] COMMAND [ARGS]

 The most commonly used perf commands are:
   annotate        Read perf.data (created by perf record) and display annotated code
   archive         Create archive with object files with build-ids found in perf.data file
   bench           General framework for benchmark suites
   buildid-cache   Manage build-id cache.
   buildid-list    List the buildids in a perf.data file
   c2c             Shared Data C2C/HITM Analyzer.
   config          Get and set variables in a configuration file.
   daemon          Run record sessions on background
   data            Data file related processing
   diff            Read perf.data files and display the differential profile
   evlist          List the event names in a perf.data file
   ftrace          simple wrapper for kernel's ftrace functionality
   inject          Filter to augment the events stream with additional information
   iostat          Show I/O performance metrics
   kallsyms        Searches running kernel for symbols
   kvm             Tool to trace/measure kvm guest os
   list            List all symbolic event types
   mem             Profile memory accesses
   record          Run a command and record its profile into perf.data
   report          Read perf.data (created by perf record) and display the profile
   script          Read perf.data (created by perf record) and display trace output
   stat            Run a command and gather performance counter statistics
   test            Runs sanity tests.
   top             System profiling tool.
   version         display the version of perf binary
   probe           Define new dynamic tracepoints
   trace           strace inspired tool
   kmem            Tool to trace/measure kernel memory properties
   kwork           Tool to trace/measure kernel work properties (latencies)
   lock            Analyze lock events
   sched           Tool to trace/measure scheduler properties (latencies)
   timechart       Tool to visualize total system behavior during a workload

 See 'perf help COMMAND' for more information on a specific command. ·  · 

**Examples:**


---

## Code Standards

| Standard | Requirement |
|----------|-------------|
| Language | TypeScript (strict mode, no  types) |
| Tests | Minimum 80% coverage for new code |
| Linting | Zero warnings () |
| Formatting | Prettier default config |
| Security | No hardcoded secrets, validate all inputs |
| Commits | GPG or SSH signed |

---

## Code Review Process

All pull requests require at least one review before merging. Reviewers evaluate:

- Correctness and business logic
- Security implications and OWASP compliance
- Test coverage and quality
- Performance impact
- Code readability and maintainability
- API backward compatibility

Pull requests must pass all CI checks (lint, test, build, security scan) before review.

---

## Security Vulnerabilities

**DO NOT open public issues for security vulnerabilities.**

See [SECURITY.md](SECURITY.md) for responsible disclosure instructions, or email [security@ailydian.com](mailto:security@ailydian.com) directly.

---

## Questions?

For contribution inquiries not covered here, contact [info@ailydian.com](mailto:info@ailydian.com).
