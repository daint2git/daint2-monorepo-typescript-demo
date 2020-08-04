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
