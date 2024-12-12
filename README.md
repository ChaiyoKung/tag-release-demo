# Tag/Release Demo

## Project setup

```bash
$ pnpm install
```

## Compile and run the project

```bash
# development
$ pnpm run start

# watch mode
$ pnpm run start:dev

# production mode
$ pnpm run start:prod
```

## Run tests

```bash
# unit tests
$ pnpm run test

# e2e tests
$ pnpm run test:e2e

# test coverage
$ pnpm run test:cov
```

## Tag

```bash
# tag `v1.1.0` at latest commit
git tag v1.1.0
git push origin v1.1.0

# move tag `v1` to latest commit
git tag -d v1
git push -d origin v1
git tag v1
git push origin v1
```
