# website

## How to render prod version

```bash
hugo --gc --minify
```

## How to run development

### required tools

- pnpm: https://pnpm.io/
- hugo: https://gohugo.io/

### first time setup

https://github.com/nusserstudios/tailbliss#-quick-start

```bash
git submodule update --init --recursive

cd src

# Install dependencies and build CSS (use pnpm or npm)
cd themes/tailbliss
pnpm install
pnpm run build:css:dev
cp static/css/main.*.css ../../static/css/
cd ../..

hugo server
```

### How to run

```bash
cd src
hugo server
```
