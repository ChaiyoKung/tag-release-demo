# Tag/Release Demo

## Project setup

```bash
bun install
```

## Run the project

```bash
# development mode
bun dev

# production mode
bun start
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
