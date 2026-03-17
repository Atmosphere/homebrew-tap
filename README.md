# Atmosphere Homebrew Tap

Homebrew formulae for the [Atmosphere](https://github.com/Atmosphere/atmosphere) real-time Java framework.

## Install

```bash
brew install Atmosphere/tap/atmosphere
```

## What you get

The `atmosphere` CLI — run samples, scaffold projects, and explore the framework:

```bash
atmosphere list                          # See all samples
atmosphere run spring-boot-chat          # Build & run a sample
atmosphere run spring-boot-ai-chat --env LLM_API_KEY=sk-xxx
atmosphere new my-app                    # Scaffold a project
```

Samples are built from source on first run and cached locally for instant subsequent starts.

## Requirements

- Java 21+ (installed automatically as a dependency)
- macOS or Linux
