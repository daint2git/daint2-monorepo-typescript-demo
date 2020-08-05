# daint2-monorepo-typescript-demo

## npm

### log in to a organization

```bash
npm login --scope=organization-name
```

## lerna

```bash
npm install -g lerna
```

```bash
lerna add

lerna add ts-node --scope=@daint2-monorepo-typescript-demo/integration --dev
```

```bash
# -W: --ignore-workspace-root-check
yarn add @commitlint/cli @commitlint/config-conventional @commitlint/config-lerna-scopes -W --dev
```

```bash
# change log
yarn lerna-changelog

yarn lerna-changelog --from=v1.0.0 --to=v2.0.0
```

```bash
# publish with --conventional-commits
yarn lerna publish --conventional-commits
```
