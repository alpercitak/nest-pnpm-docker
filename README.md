# nest-pnpm-docker

![Build](https://github.com/alpercitak/nest-pnpm-docker/actions/workflows/build.yaml/badge.svg)
![Lint](https://github.com/alpercitak/nest-pnpm-docker/actions/workflows/lint.yaml/badge.svg)
![Test](https://github.com/alpercitak/nest-pnpm-docker/actions/workflows/test.yaml/badge.svg)
![License](https://img.shields.io/github/license/alpercitak/nest-pnpm-docker)

NestJS Docker configuration using pnpm. Companion repository for the Medium article [NestJS: Use pnpm on Docker](https://medium.com/@alpercitak/nest-js-use-pnpm-on-docker-81998ab4d8a1).

## Setup

```bash
pnpm install
```

## Development

```bash
pnpm start         # standard
pnpm start:dev     # watch mode
pnpm start:prod    # production
```

## Test

```bash
pnpm test          # unit tests
pnpm test:e2e      # e2e tests
pnpm test:cov      # coverage
```

## Docker

```bash
docker compose up
```

## License

MIT
