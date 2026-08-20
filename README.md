# SimplyLearning Starter

This is my simple Rails and opencode starter template.

It provides a small Rails application foundation with the tools and conventions I want available before building product features.

## What Is Included

- Rails 8 application structure
- PostgreSQL configuration
- Devise authentication
- Hotwire and Stimulus defaults
- Tailwind CSS build setup
- Solid Queue, Solid Cache, and Solid Cable schema files
- Kamal deployment scaffolding
- opencode project instructions in `AGENTS.md`

## Local Development

Install dependencies and prepare the app:

```sh
bin/setup
```

Run the development server:

```sh
bin/dev
```

Run tests:

```sh
bin/rails test
```

Run the project checks used by CI:

```sh
bin/ci
```

## Notes

This template is intended to stay small and practical. It is a clean starting point for Rails apps that use opencode as a coding-agent workflow companion.
