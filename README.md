Copy configs:

```
npx degit kitsupanic/js-configs/files --force
```

Install deps:

```
pnpm add -D eslint @eslint/js @eslint/json @eslint/markdown @stylistic/eslint-plugin globals jiti prettier prettier-plugin-organize-imports prettier-plugin-sort-json typescript typescript-eslint
```

npm scripts:

```
    "format": "prettier . --write",
    "lint": "eslint --fix",
    "bonita": "pnpm run lint && pnpm run format"
```
